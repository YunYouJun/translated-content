---
title: Set.prototype.delete()
slug: Web/JavaScript/Reference/Global_Objects/Set/delete
translation_of: Web/JavaScript/Reference/Global_Objects/Set/delete
original_slug: Web/JavaScript/Referencia/Objetos_globales/Set/delete
---
{{JSRef}}

El método **`delete()`** remueve el elemento especificado del objeto `Set`.

## Syntaxis

    mySet.delete(value);

### Parametros

- valor
  - : Requerido. El valor del elemento a remover del objeto `Set`.

### Valor de retorno

`true` si el elemento ha sido removido exitosamente en el `Set`; de otra manera retorna `false`.

## Ejemplos

### Usando el método `delete`

```js
var mySet = new Set();
mySet.add("foo");

mySet.delete("bar"); // Retorna false. No hay elemento "bar" para ser removido.
mySet.delete("foo"); // Retorna true.  Removido exitosamente.

mySet.has("foo");    // Retorna false. El elemento "foo" ya no está presente.
```

## Especificaciones

| Especificación                                                                                       | Estado                       | Comentario          |
| ---------------------------------------------------------------------------------------------------- | ---------------------------- | ------------------- |
| {{SpecName('ES6', '#sec-set.prototype.delete', 'Set.prototype.delete')}}     | {{Spec2('ES6')}}         | Definición inicial. |
| {{SpecName('ESDraft', '#sec-set.prototype.delete', 'Set.prototype.delete')}} | {{Spec2('ESDraft')}} |                     |

## Compatibilidad de navegadores

{{Compat("javascript.builtins.Set.delete")}}

## Ver también

- {{jsxref("Set")}}
- {{jsxref("Set.prototype.clear()")}}
