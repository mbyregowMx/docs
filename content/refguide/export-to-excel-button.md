---
title: "Export to Excel Button"
parent: "control-bar"
menu_order: 80
tags: ["studio pro"]
#If moving or renaming this doc file, implement a temporary redirect and let the respective team know they should update the URL in the product. See Mapping to Products for more details.
---


This button allows end-users to export the contents of the grid or reference set selector to an excel file. Please note that constraints by use of search fields and sorting will also be exported.

The excel export function relies on a specific data retrieval method. As such, it is only available in list widgets that use the XPath data source. 

## Common properties

{{% snippet file="refguide/class+property.md" %}}

{{% snippet file="refguide/Style+Property.md" %}}

## General properties

{{% snippet file="refguide/caption+property.md" %}}

{{% snippet file="refguide/Tooltip+Property.md" %}}

{{% snippet file="refguide/image+property.md" %}}

{{% snippet file="refguide/button+style+property.md" %}}

{{% snippet file="refguide/is+default+button+property.md" %}}

### Maximum number of rows

Indicates the maximum number of rows that can be present in the datagrid when exporting. Useful to prevent users from exporting large quantities of data, potentially placing a heavy load on the server.

### Date export format

Defines how dates will be exported. When _Date value_ is selected, date values will be exported as real dates, so that it is possible to use Excel date functions like sorting. When _Text_ is selected, date values will be exported exactly as shown in the data grid.

_Default value:_ Date value

{{% alert type="warning" %}}

When choosing _Date value_, dates will be shown only in the time zone of your Windows account, because Excel does not support defining specific time zones.

{{% /alert %}}

## Visibility properties

{{% snippet file="refguide/Visibility+Property.md" %}}

{{% snippet file="refguide/Visibility+Property+With+Module+Roles+Simple.md" %}}
