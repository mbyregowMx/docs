---
title: "Comparison Search Field"
parent: "search-bar"
tags: ["studio pro"]
#If moving or renaming this doc file, implement a temporary redirect and let the respective team know they should update the URL in the product. See Mapping to Products for more details.
---

## Introduction

To add a comparison search field to your data grid, right-click within the search bar in your data grid and choose **Add search field > Comparison**.

## Common Properties

{{% snippet file="refguide/Search+Field+Caption+Property.md" %}}

{{% snippet file="refguide/Search+Field+Type+Property.md" %}}

{{% snippet file="refguide/Search+Field+Default+Value+Property.md" %}}

{{% snippet file="refguide/Search+Field+Custom+Date+Format+Property.md" %}}

{{% snippet file="refguide/custom+date+format+tokens.md" %}}

{{% snippet file="refguide/Search+Field+Placeholder+Property.md" %}}

## General Properties

{{% snippet file="refguide/Search+Field+Attribute+Path+Property.md" %}}

{{% snippet file="refguide/Search+Field+Comparison+Property.md" %}}

### Date comparisons and the influence of the default value

It is possible to search on date attributes using equality. What happens with the time component belonging to the date is dependent on the default value of the comparison search field.

| Default value | Search query |   | Result example (input: August 4, 2100) |
| --- | --- | --- | --- |
| None | Search field is empty. Represents a 24 hour date range starting at midnight of the specified date. |   | Search between August 4, 0:00 - August 5, 0:00 |
| [%CurrentDateTime%] | Search field shows the current date. Represents a 24 hour date range starting at the _current time_. |   | Search between August 4, <current time> and August 5, <current time> |
| [%BeginOfCurrentDay%] | Search field shows the current date. Represents a 24 hour date range starting at midnight of the specified date. |   | Search between August 4, 0:00 - August 5, 0:00 |
