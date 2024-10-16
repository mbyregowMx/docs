---
title: "Group Box"
parent: "container-widgets"
menu_order: 30
tags: ["studio pro"]
#If moving or renaming this doc file, implement a temporary redirect and let the respective team know they should update the URL in the product. See Mapping to Products for more details.
---

{{% alert type="warning" %}}The group box widget is not supported on native mobile pages.{{% /alert %}}

A group box can be used to visually group related widgets together. Group boxes are displayed as a frame around nested widgets with an optional header. Group boxes can be configured to collapse and expand dynamically.

{{% alert type="info" %}}

![](attachments/16713857/16843974.jpg)
An empty group box.

{{% /alert %}}

## Common properties

{{% snippet file="refguide/name+property.md" %}}

{{% snippet file="refguide/class+property.md" %}}

{{% snippet file="refguide/Style+Property.md" %}}

## General properties

### Show header

Toggle whether a header is shown above the group box.

_Default value:_ True

### Caption

The text of the header. This property is only applicable if the header is visible.

_Default value:_ Group box

### Collapsible

This property specifies whether the group box can be collapsed by clicking the header and if so, whether it starts collapsed or expanded. This property is only applicable if the header is visible.

_Default value:_ Yes (start expanded)

## Visibility properties

{{% snippet file="refguide/Visibility+Property.md" %}}

{{% snippet file="refguide/Visibility+Property+With+Module+Roles+Simple.md" %}}
