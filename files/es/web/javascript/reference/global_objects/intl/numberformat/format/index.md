---
title: Intl.NumberFormat.prototype.format()
slug: Web/JavaScript/Reference/Global_Objects/Intl/NumberFormat/format
translation_of: Web/JavaScript/Reference/Global_Objects/Intl/NumberFormat/format
original_slug: Web/JavaScript/Referencia/Objetos_globales/Intl/NumberFormat/format
---
{{JSRef}}

El método **`Intl.NumberFormat.prototype.format()`** formatea un número de acuerdo con la configuración regional y las opciones de formato de este objeto {{jsxref("NumberFormat")}}.

{{EmbedInteractiveExample("pages/js/intl-numberformat-prototype-format.html")}}

## Syntax

    numberFormat.format(number)

### Parametros

- `number`
  - : A {{jsxref("Number")}} or {{jsxref("BigInt")}} to format.

## Descripción

The `format` getter function formats a number into a string according to the locale and formatting options of this {{jsxref("NumberFormat")}} object.

## Ejemplos

### Usando `format`

Use the `format` getter function for formatting a single currency value, here for Russia:

```js
var options = { style: 'currency', currency: 'RUB' };
var numberFormat = new Intl.NumberFormat('ru-RU', options);
console.log(numberFormat.format(654321.987));
// → "654 321,99 руб."
```

### Usando `format` con `map`

Use the `format` getter function for formatting all numbers in an array. Note that the function is bound to the {{jsxref("NumberFormat")}} from which it was obtained, so it can be passed directly to {{jsxref("Array.prototype.map")}}.

```js
var a = [123456.789, 987654.321, 456789.123];
var numberFormat = new Intl.NumberFormat('es-ES');
var formatted = a.map(numberFormat.format);
console.log(formatted.join('; '));
// → "123.456,789; 987.654,321; 456.789,123"
```

## Especificaciones

| Specification                                                                                                                                    | Status                           | Comment             |
| ------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------- | ------------------- |
| {{SpecName('ES Int 1.0', '#sec-11.3.2', 'Intl.NumberFormat.prototype.format')}}                                         | {{Spec2('ES Int 1.0')}} | Initial definition. |
| {{SpecName('ES Int 2.0', '#sec-11.3.2', 'Intl.NumberFormat.prototype.format')}}                                         | {{Spec2('ES Int 2.0')}} |                     |
| {{SpecName('ES Int Draft', '#sec-intl.numberformat.prototype.format', 'Intl.NumberFormat.prototype.format')}} | {{Spec2('ES Int Draft')}} |                     |

## Browser compatibility

{{Compat("javascript.builtins.Intl.NumberFormat.format")}}

## See also

- {{jsxref("NumberFormat", "Intl.NumberFormat")}}
- {{jsxref("Number.prototype.toLocaleString()")}}
