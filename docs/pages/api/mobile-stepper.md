---
filename: /packages/material-ui/src/MobileStepper/MobileStepper.js
---

<!--- This documentation is automatically generated, do not try to edit it. -->

# MobileStepper API

<p class="description">The API documentation of the MobileStepper React component. Learn more about the properties and the CSS customization points.</p>

```js
import { MobileStepper } from '@material-ui/core';
```



## Props

| Name | Type | Default | Description |
|:-----|:-----|:--------|:------------|
| <span class="prop-name">activeStep</span> | <span class="prop-type">number</span> | <span class="prop-default">0</span> | Set the active step (zero based index). Defines which dot is highlighted when the variant is 'dots'. |
| <span class="prop-name">backButton</span> | <span class="prop-type">node</span> |  | A back button element. For instance, it can be a `Button` or an `IconButton`. |
| <span class="prop-name">classes</span> | <span class="prop-type">object</span> |  | Override or extend the styles applied to the component. See [CSS API](#css) below for more details. |
| <span class="prop-name">LinearProgressProps</span> | <span class="prop-type">object</span> |  | Props applied to the `LinearProgress` element. |
| <span class="prop-name">nextButton</span> | <span class="prop-type">node</span> |  | A next button element. For instance, it can be a `Button` or an `IconButton`. |
| <span class="prop-name">position</span> | <span class="prop-type">enum:&nbsp;'bottom'&nbsp;&#124;<br>&nbsp;'top'&nbsp;&#124;<br>&nbsp;'static'<br></span> | <span class="prop-default">'bottom'</span> | Set the positioning type. |
| <span class="prop-name required">steps&nbsp;*</span> | <span class="prop-type">number</span> |  | The total steps. |
| <span class="prop-name">variant</span> | <span class="prop-type">enum:&nbsp;'text'&nbsp;&#124;<br>&nbsp;'dots'&nbsp;&#124;<br>&nbsp;'progress'<br></span> | <span class="prop-default">'dots'</span> | The variant to use. |

The `ref` is forwarded to the root element.

Any other properties supplied will be provided to the root element ([Paper](/api/paper/)).

## CSS

- Style sheet name: `MuiMobileStepper`.
- Style sheet details:

| Rule name | Global class | Description |
|:-----|:-------------|:------------|
| <span class="prop-name">root</span> | <span class="prop-name">MuiMobileStepper-root</span> | Styles applied to the root element.
| <span class="prop-name">positionBottom</span> | <span class="prop-name">MuiMobileStepper-positionBottom</span> | Styles applied to the root element if `position="bottom"`.
| <span class="prop-name">positionTop</span> | <span class="prop-name">MuiMobileStepper-positionTop</span> | Styles applied to the root element if `position="top"`.
| <span class="prop-name">positionStatic</span> | <span class="prop-name">MuiMobileStepper-positionStatic</span> | Styles applied to the root element if `position="static"`.
| <span class="prop-name">dots</span> | <span class="prop-name">MuiMobileStepper-dots</span> | Styles applied to the dots container if `variant="dots"`.
| <span class="prop-name">dot</span> | <span class="prop-name">MuiMobileStepper-dot</span> | Styles applied to each dot if `variant="dots"`.
| <span class="prop-name">dotActive</span> | <span class="prop-name">MuiMobileStepper-dotActive</span> | Styles applied to a dot if `variant="dots"` and this is the active step.
| <span class="prop-name">progress</span> | <span class="prop-name">MuiMobileStepper-progress</span> | Styles applied to the Linear Progress component if `variant="progress"`.

You can override the style of the component thanks to one of these customizability points:

- With a rule name of the [`classes` object prop](/customization/components/#overriding-styles-with-classes).
- With a [global class name](/customization/components/#overriding-styles-with-global-class-names).
- With a theme and an [`overrides` property](/customization/globals/#css).

If it's not enough, you can find the [implementation of the component](https://github.com/mui-org/material-ui/blob/master/packages/material-ui/src/MobileStepper/MobileStepper.js) for more detail.

## Inheritance

The properties of the [Paper](/api/paper/) component are also available.
You can take advantage of this behavior to [target nested components](/guides/api/#spread).

## Notes

The component is fully [StrictMode](https://reactjs.org/docs/strict-mode.html) compatible.

## Demos

- [Steppers](/components/steppers/)

