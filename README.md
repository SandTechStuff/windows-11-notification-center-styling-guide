# The Windows 11 notification center styling guide

*This document is a work in progress, contributions are welcome.* \
***See also**: [The Windows 11 taskbar styling
guide](https://github.com/ramensoftware/windows-11-taskbar-styling-guide/blob/main/README.md),
[The Windows 11 start menu styling
guide](https://github.com/ramensoftware/windows-11-start-menu-styling-guide/blob/main/README.md).*

## Table of contents

* [Introduction](#introduction)
* [Themes](#themes)
* [Style examples](#style-examples)
* [Work in progress](#work-in-progress)

## Introduction

This is a collection of commonly requested notification center styling
customizations for Windows 11. It is intended to be used with the [Windows 11
Notification Center
Styler](https://windhawk.net/mods/windows-11-notification-center-styler)
Windhawk mod.

If you're not familiar with Windhawk, here are the steps for installing the mod:

* Download Windhawk from [windhawk.net](https://windhawk.net/) and install it.
* Go to "Mods" in the upper right menu.
* Find and install the "Windows 11 Notification Center Styler" mod.

After installing the mod, open its Settings tab and adjust the styles according
to your preferences.

Some customizations are best to be adjusted with other Windhawk mods. Links to
those mods are provided where applicable.

### Missing customizations

If you're looking for a customization that is not listed here, please [open an
issue](https://github.com/ramensoftware/windows-11-notification-center-styling-guide/issues/new).

### Contributing

If you have a notification center styling customization or theme that you would
like to share, please submit a pull request.

## Themes

Themes are collections of styles that can be imported into the Windows 11
Notification Center Styler mod. The following themes are available:

| Link | Screenshot
| ---- | ----------
| [TranslucentShell](Themes/TranslucentShell/README.md) | [![TranslucentShell](Themes/TranslucentShell/screenshot-small.png)](Themes/TranslucentShell/video.gif)
| [Unified](Themes/Unified/README.md) | [![Unified](Themes/Unified/screenshot-small.png)](Themes/Unified/screenshot.png)
| [10JumpLists](Themes/10JumpLists/README.md) | [![10JumpLists](Themes/10JumpLists/screenshot-small.png)](Themes/10JumpLists/screenshot.png)

## Style examples

### Hide the focus assist section
**Target**: `ActionCenter.FocusSessionControl` \
**Style**: `Height=0`

### Hide the notification center
**Target**: `Grid#NotificationCenterGrid` \
**Style**: `Visibility=Collapsed`

### Shrink the notification center height
Makes panel non full-height when there are fewer notifications (fit to size). \
**Target**: `Grid#NotificationCenterGrid` \
**Style**: `VerticalAlignment=2`

### Square the corners of the notification center
**Target**: `Grid#NotificationCenterGrid` \
**Style**: `CornerRadius=0`

### Square the corners of the calendar
**Target**: `Grid#CalendarCenterGrid` \
**Style**: `CornerRadius=0`

### Square the corners of the quick action center
**Target**: `Grid#ControlCenterRegion` \
**Style**: `CornerRadius=0`

### Calendar and notification titlebars: titles on the right, buttons on the left
**Target**: `Grid#RootContent` \
**Style**: `FlowDirection=1`

### Add accelerator key (Alt+X) to clear all notifications
**Target**: `Button#ClearAll` \
**Style**: `AccessKey=x`

### Add accelerator key (Alt+E) to expand/collapse the calendar
**Target**: `Button#ExpandCollapseButton` \
**Style**: `AccessKey=e`

## Work in progress

*This document is a work in progress, contributions are welcome.* \
***See also**: [The Windows 11 taskbar styling
guide](https://github.com/ramensoftware/windows-11-taskbar-styling-guide/blob/main/README.md),
[The Windows 11 start menu styling
guide](https://github.com/ramensoftware/windows-11-start-menu-styling-guide/blob/main/README.md).*
