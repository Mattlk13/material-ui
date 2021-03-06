---
filename: /packages/material-ui/src/Typography/Typography.js
---

<!--- This documentation is automatically generated, do not try to edit it. -->

# Typography API

<p class="description">The API documentation of the Typography React component. Learn more about the properties and the CSS customization points.</p>

```js
import { Typography } from '@material-ui/core';
```



## Props

| Name | Type | Default | Description |
|:-----|:-----|:--------|:------------|
| <span class="prop-name">align</span> | <span class="prop-type">enum:&nbsp;'inherit', 'left', 'center', 'right', 'justify'<br></span> | <span class="prop-default">'inherit'</span> | Set the text-align on the component. |
| <span class="prop-name">children</span> | <span class="prop-type">node</span> |  | The content of the component. |
| <span class="prop-name">classes</span> | <span class="prop-type">object</span> |  | Override or extend the styles applied to the component. See [CSS API](#css) below for more details. |
| <span class="prop-name">color</span> | <span class="prop-type">enum:&nbsp;'initial', 'inherit', 'primary', 'secondary', 'textPrimary', 'textSecondary', 'error'<br></span> | <span class="prop-default">'initial'</span> | The color of the component. It supports those theme colors that make sense for this component. |
| <span class="prop-name">component</span> | <span class="prop-type">elementType</span> |  | The component used for the root node. Either a string to use a DOM element or a component. By default, it maps the variant to a good default headline component. |
| <span class="prop-name">display</span> | <span class="prop-type">enum:&nbsp;'initial'&nbsp;&#124;<br>&nbsp;'block'&nbsp;&#124;<br>&nbsp;'inline'<br></span> | <span class="prop-default">'initial'</span> | Controls the display type |
| <span class="prop-name">gutterBottom</span> | <span class="prop-type">bool</span> | <span class="prop-default">false</span> | If `true`, the text will have a bottom margin. |
| <span class="prop-name">noWrap</span> | <span class="prop-type">bool</span> | <span class="prop-default">false</span> | If `true`, the text will not wrap, but instead will truncate with an ellipsis. |
| <span class="prop-name">paragraph</span> | <span class="prop-type">bool</span> | <span class="prop-default">false</span> | If `true`, the text will have a bottom margin. |
| <span class="prop-name">variant</span> | <span class="prop-type">enum:&nbsp;'h1', 'h2', 'h3', 'h4', 'h5', 'h6', 'subtitle1', 'subtitle2', 'body1', 'body2', 'caption', 'button', 'overline', 'srOnly', 'inherit'<br></span> | <span class="prop-default">'body1'</span> | Applies the theme typography styles. |
| <span class="prop-name">variantMapping</span> | <span class="prop-type">object</span> | <span class="prop-default">{  h1: 'h1',  h2: 'h2',  h3: 'h3',  h4: 'h4',  h5: 'h5',  h6: 'h6',  subtitle1: 'h6',  subtitle2: 'h6',  body1: 'p',  body2: 'p',}</span> | We are empirically mapping the variant prop to a range of different DOM element types. For instance, subtitle1 to `<h6>`. If you wish to change that mapping, you can provide your own. Alternatively, you can use the `component` prop. |

The `ref` is forwarded to the root element.

Any other properties supplied will be provided to the root element (native element).

## CSS

- Style sheet name: `MuiTypography`.
- Style sheet details:

| Rule name | Global class | Description |
|:-----|:-------------|:------------|
| <span class="prop-name">root</span> | <span class="prop-name">MuiTypography-root</span> | Styles applied to the root element.
| <span class="prop-name">body2</span> | <span class="prop-name">MuiTypography-body2</span> | Styles applied to the root element if `variant="body2"`.
| <span class="prop-name">body1</span> | <span class="prop-name">MuiTypography-body1</span> | Styles applied to the root element if `variant="body1"`.
| <span class="prop-name">caption</span> | <span class="prop-name">MuiTypography-caption</span> | Styles applied to the root element if `variant="caption"`.
| <span class="prop-name">button</span> | <span class="prop-name">MuiTypography-button</span> | Styles applied to the root element if `variant="button"`.
| <span class="prop-name">h1</span> | <span class="prop-name">MuiTypography-h1</span> | Styles applied to the root element if `variant="h1"`.
| <span class="prop-name">h2</span> | <span class="prop-name">MuiTypography-h2</span> | Styles applied to the root element if `variant="h2"`.
| <span class="prop-name">h3</span> | <span class="prop-name">MuiTypography-h3</span> | Styles applied to the root element if `variant="h3"`.
| <span class="prop-name">h4</span> | <span class="prop-name">MuiTypography-h4</span> | Styles applied to the root element if `variant="h4"`.
| <span class="prop-name">h5</span> | <span class="prop-name">MuiTypography-h5</span> | Styles applied to the root element if `variant="h5"`.
| <span class="prop-name">h6</span> | <span class="prop-name">MuiTypography-h6</span> | Styles applied to the root element if `variant="h6"`.
| <span class="prop-name">subtitle1</span> | <span class="prop-name">MuiTypography-subtitle1</span> | Styles applied to the root element if `variant="subtitle1"`.
| <span class="prop-name">subtitle2</span> | <span class="prop-name">MuiTypography-subtitle2</span> | Styles applied to the root element if `variant="subtitle2"`.
| <span class="prop-name">overline</span> | <span class="prop-name">MuiTypography-overline</span> | Styles applied to the root element if `variant="overline"`.
| <span class="prop-name">srOnly</span> | <span class="prop-name">MuiTypography-srOnly</span> | Styles applied to the root element if `variant="srOnly"`. Only accessible to screen readers.
| <span class="prop-name">alignLeft</span> | <span class="prop-name">MuiTypography-alignLeft</span> | Styles applied to the root element if `align="left"`.
| <span class="prop-name">alignCenter</span> | <span class="prop-name">MuiTypography-alignCenter</span> | Styles applied to the root element if `align="center"`.
| <span class="prop-name">alignRight</span> | <span class="prop-name">MuiTypography-alignRight</span> | Styles applied to the root element if `align="right"`.
| <span class="prop-name">alignJustify</span> | <span class="prop-name">MuiTypography-alignJustify</span> | Styles applied to the root element if `align="justify"`.
| <span class="prop-name">noWrap</span> | <span class="prop-name">MuiTypography-noWrap</span> | Styles applied to the root element if `align="nowrap"`.
| <span class="prop-name">gutterBottom</span> | <span class="prop-name">MuiTypography-gutterBottom</span> | Styles applied to the root element if `gutterBottom={true}`.
| <span class="prop-name">paragraph</span> | <span class="prop-name">MuiTypography-paragraph</span> | Styles applied to the root element if `paragraph={true}`.
| <span class="prop-name">colorInherit</span> | <span class="prop-name">MuiTypography-colorInherit</span> | Styles applied to the root element if `color="inherit"`.
| <span class="prop-name">colorPrimary</span> | <span class="prop-name">MuiTypography-colorPrimary</span> | Styles applied to the root element if `color="primary"`.
| <span class="prop-name">colorSecondary</span> | <span class="prop-name">MuiTypography-colorSecondary</span> | Styles applied to the root element if `color="secondary"`.
| <span class="prop-name">colorTextPrimary</span> | <span class="prop-name">MuiTypography-colorTextPrimary</span> | Styles applied to the root element if `color="textPrimary"`.
| <span class="prop-name">colorTextSecondary</span> | <span class="prop-name">MuiTypography-colorTextSecondary</span> | Styles applied to the root element if `color="textSecondary"`.
| <span class="prop-name">colorError</span> | <span class="prop-name">MuiTypography-colorError</span> | Styles applied to the root element if `color="error"`.
| <span class="prop-name">displayInline</span> | <span class="prop-name">MuiTypography-displayInline</span> | Styles applied to the root element if `display="inline"`.
| <span class="prop-name">displayBlock</span> | <span class="prop-name">MuiTypography-displayBlock</span> | Styles applied to the root element if `display="block"`.

You can override the style of the component thanks to one of these customizability points:

- With a rule name of the [`classes` object prop](/customization/components/#overriding-styles-with-classes).
- With a [global class name](/customization/components/#overriding-styles-with-global-class-names).
- With a theme and an [`overrides` property](/customization/globals/#css).

If it's not enough, you can find the [implementation of the component](https://github.com/mui-org/material-ui/blob/master/packages/material-ui/src/Typography/Typography.js) for more detail.

## Notes

The component is fully [StrictMode](https://reactjs.org/docs/strict-mode.html) compatible.

## Demos

- [Breadcrumbs](/components/breadcrumbs/)
- [Typography](/components/typography/)

