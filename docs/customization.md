---
title: Customization
description: "Refer to the list of the Kendo UI Bootstrap theme variables available for customization."
slug: variables_kendothemebootstrap_kendouiforangular
position: 9
---

# Customization

The following list describes the theme variables available for adjustment in the Kendo UI Bootstrap theme for Angular.

<style>
.theme-variables th,
.theme-variables td {
  vertical-align: top;
}

.color-preview {
  border-radius: 50%;
  width: 1em;
  height: 1em;
  vertical-align: middle;
  display: inline-block;
  border: 1px solid rgba(0,0,0,.08);
}
</style>

## Variables


### Common

<table class="theme-variables">
<colgroup>
<col style="white-space:nowrap; width: 200px" />
<col style="width: 250px" />
<col />
</colgroup>
<tr>
<th>Name</th>
<th>Default value</th>
<th>Description</th>
</tr>
<tr>
<td>$font-size</td>
<td>

    $font-size-base
</td>
<td>Base font size across all components.
</td>
</tr>
<tr>
<td>$font-family</td>
<td>

    $font-family-base
</td>
<td>Font family across all components.
</td>
</tr>
<tr>
<td>$font-family-monospace</td>
<td>

    $font-family-monospace
</td>
<td>Font family for monospaced text. Used for styling the code.
</td>
</tr>
<tr>
<td>$line-height</td>
<td>

    $line-height-base
</td>
<td>Line height used along with $font-size.
</td>
</tr>
<tr>
<td>$border-radius</td>
<td>

    $border-radius
</td>
<td>Border radius for all components.
</td>
</tr>
<tr>
<td>$accent</td>
<td>

    $component-active-bg
</td>
<td>The color that focuses the user attention.<br/>
Used for primary buttons and for elements of primary importance across the theme.
</td>
</tr>
<tr>
<td>$accent-contrast</td>
<td>

    $component-active-color
</td>
<td>The color used along with the accent color denoted by $accent.<br/>
Used to provide contrast between the background and foreground colors.
</td>
</tr>
<tr>
<td>$base-text</td>
<td>

    $btn-secondary-color
</td>
<td>The text color of the components' chrome area.
</td>
</tr>
<tr>
<td>$base-bg</td>
<td>

    $btn-secondary-bg
</td>
<td>The background of the components' chrome area.
</td>
</tr>
<tr>
<td>$base-border</td>
<td>

    darken( $base-bg, 12% )
</td>
<td>The border color of the components' chrome area.
</td>
</tr>
<tr>
<td>$base-gradient</td>
<td>

    none
</td>
<td>The gradient background of the components' chrome area.
</td>
</tr>
<tr>
<td>$hovered-text</td>
<td>

    $base-text
</td>
<td>The text color of hovered items.
</td>
</tr>
<tr>
<td>$hovered-bg</td>
<td>

    darken( $base-bg, 3% )
</td>
<td>The background of hovered items.
</td>
</tr>
<tr>
<td>$hovered-border</td>
<td>

    darken( $base-border, 12% )
</td>
<td>The border color of hovered items.
</td>
</tr>
<tr>
<td>$hovered-gradient</td>
<td>

    none
</td>
<td>The gradient background of hovered items.
</td>
</tr>
<tr>
<td>$selected-text</td>
<td>

    $accent-contrast
</td>
<td>The text color of selected items.
</td>
</tr>
<tr>
<td>$selected-bg</td>
<td>

    $accent
</td>
<td>The background of selected items.
</td>
</tr>
<tr>
<td>$selected-border</td>
<td>

    darken( $selected-bg, 12% )
</td>
<td>The border color of selected items.
</td>
</tr>
<tr>
<td>$selected-gradient</td>
<td>

    none
</td>
<td>The gradient background of selected items.
</td>
</tr>
<tr>
<td>$success</td>
<td>

    $brand-success
</td>
<td>The color for error messages and states.
</td>
</tr>
<tr>
<td>$info</td>
<td>

    $brand-info
</td>
<td>The color for warning messages and states.
</td>
</tr>
<tr>
<td>$warning</td>
<td>

    $brand-warning
</td>
<td>The color for success messages and states.
</td>
</tr>
<tr>
<td>$error</td>
<td>

    $brand-danger
</td>
<td>The color for informational messages and states.
</td>
</tr>
</table>


### Buttons

<table class="theme-variables">
<colgroup>
<col style="white-space:nowrap; width: 200px" />
<col style="width: 250px" />
<col />
</colgroup>
<tr>
<th>Name</th>
<th>Default value</th>
<th>Description</th>
</tr>
<tr>
<td>$button-text</td>
<td>

    $base-text
</td>
<td>The text color of the buttons.
</td>
</tr>
<tr>
<td>$button-bg</td>
<td>

    $base-bg
</td>
<td>The background of the buttons.
</td>
</tr>
<tr>
<td>$button-border</td>
<td>

    darken( $base-border, 8 )
</td>
<td>The border color of the buttons.
</td>
</tr>
<tr>
<td>$button-gradient</td>
<td>

    none
</td>
<td>The background gradient of the buttons.
</td>
</tr>
<tr>
<td>$button-hovered-text</td>
<td>

    $button-text
</td>
<td>The text color of hovered buttons.
</td>
</tr>
<tr>
<td>$button-hovered-bg</td>
<td>

    darken( $button-bg, 10% )
</td>
<td>The background of hovered buttons.
</td>
</tr>
<tr>
<td>$button-hovered-border</td>
<td>

    darken( $button-border, 12% )
</td>
<td>The border color of hovered buttons.
</td>
</tr>
<tr>
<td>$button-hovered-gradient</td>
<td>

    none
</td>
<td>The background gradient of hovered buttons.
</td>
</tr>
<tr>
<td>$button-pressed-text</td>
<td>

    $button-hovered-text
</td>
<td>The text color of pressed buttons.
</td>
</tr>
<tr>
<td>$button-pressed-bg</td>
<td>

    $button-hovered-bg
</td>
<td>The background color of pressed buttons.
</td>
</tr>
<tr>
<td>$button-pressed-border</td>
<td>

    $button-hovered-border
</td>
<td>The border color of pressed buttons.
</td>
</tr>
<tr>
<td>$button-pressed-gradient</td>
<td>

    none
</td>
<td>The background gradient of pressed buttons.
</td>
</tr>
<tr>
<td>$button-focused-shadow</td>
<td>

    0 0 0 2px rgba($button-border, .5)
</td>
<td>The shadow of focused buttons.
</td>
</tr>
</table>


### Charts

<table class="theme-variables">
<colgroup>
<col style="white-space:nowrap; width: 200px" />
<col style="width: 250px" />
<col />
</colgroup>
<tr>
<th>Name</th>
<th>Default value</th>
<th>Description</th>
</tr>
<tr>
<td>$series-a</td>
<td>
    <span class="color-preview" style="background-color: #0275d8"></span>
    #0275d8
</td>
<td>The color of the first series.
</td>
</tr>
<tr>
<td>$series-b</td>
<td>
    <span class="color-preview" style="background-color: #5bc0de"></span>
    #5bc0de
</td>
<td>The color of the second series.
</td>
</tr>
<tr>
<td>$series-c</td>
<td>
    <span class="color-preview" style="background-color: #5cb85c"></span>
    #5cb85c
</td>
<td>The color of the third series.
</td>
</tr>
<tr>
<td>$series-d</td>
<td>
    <span class="color-preview" style="background-color: #f0ad4e"></span>
    #f0ad4e
</td>
<td>The color of the fourth series.
</td>
</tr>
<tr>
<td>$series-e</td>
<td>
    <span class="color-preview" style="background-color: #e67d4a"></span>
    #e67d4a
</td>
<td>The color of the fifth series.
</td>
</tr>
<tr>
<td>$series-f</td>
<td>
    <span class="color-preview" style="background-color: #d9534f"></span>
    #d9534f
</td>
<td>The color of the sixth series.
</td>
</tr>
<tr>
<td>$chart-major-lines</td>
<td>

    darken( $widget-border, 30% )
</td>
<td>The color of the Chart grid lines (major).
</td>
</tr>
<tr>
<td>$chart-minor-lines</td>
<td>

    darken( $widget-border, 20% )
</td>
<td>The color of the Chart grid lines (minor).
</td>
</tr>
</table>


### Toolbar

<table class="theme-variables">
<colgroup>
<col style="white-space:nowrap; width: 200px" />
<col style="width: 250px" />
<col />
</colgroup>
<tr>
<th>Name</th>
<th>Default value</th>
<th>Description</th>
</tr>
<tr>
<td>$toolbar-padding-x</td>
<td>

    $table-cell-padding / 2
</td>
<td>The horizontal padding of the container.
</td>
</tr>
<tr>
<td>$toolbar-padding-y</td>
<td>

    $table-cell-padding / 2
</td>
<td>The vertical padding of the container.
</td>
</tr>
</table>


## Mixins


## Suggested Links

* [Styling Overview]({% slug themesandstyles_kendouiforangular %})
* [Web Font Icons]({% slug icons_kendouiforangular %})
* [Preview of the Themed Components]({% slug preview_kendothemebootstrap_kendouiforangular %})
