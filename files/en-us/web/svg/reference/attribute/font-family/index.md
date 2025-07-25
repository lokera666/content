---
title: font-family
slug: Web/SVG/Reference/Attribute/font-family
page-type: svg-attribute
browser-compat: svg.global_attributes.font-family
sidebar: svgref
---

The **`font-family`** attribute indicates which font family will be used to render the text, specified as a prioritized list of font family names and/or generic family names.

> [!NOTE]
> As a presentation attribute, `font-family` also has a CSS property counterpart: {{cssxref("font-family")}}. When both are specified, the CSS property takes priority.

You can use this attribute with the following SVG elements:

- {{SVGElement("text")}}
- {{SVGElement("textPath")}}
- {{SVGElement("tspan")}}

## Examples

### Controlling SVG font family

```html
<svg viewBox="0 0 200 30" xmlns="http://www.w3.org/2000/svg">
  <text y="20" font-family="Arial, Helvetica, sans-serif">Sans serif</text>
  <text x="100" y="20" font-family="monospace">Monospace</text>
</svg>
```

{{EmbedLiveSample}}

## Usage notes

<table class="properties">
  <tbody>
    <tr>
      <th scope="row">Value</th>
      <td>See {{cssxref("font-family", "", "#formal_syntax")}}</td>
    </tr>
    <tr>
      <th scope="row">Default value</th>
      <td>Depends on user agent</td>
    </tr>
    <tr>
      <th scope="row">Animatable</th>
      <td>Yes</td>
    </tr>
  </tbody>
</table>

For a description of the values, please refer to the [CSS `font-family`](/en-US/docs/Web/CSS/font-family#values) property.

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}

## See also

- CSS {{cssxref("font-family")}} property
