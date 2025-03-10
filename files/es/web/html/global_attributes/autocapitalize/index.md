---
title: autocapitalización
slug: Web/HTML/Global_attributes/autocapitalize
tags:
  - Atributos globales
  - HTML
  - Reference
  - Referencia
  - autocapitalización
translation_of: Web/HTML/Global_attributes/autocapitalize
original_slug: Web/HTML/Atributos_Globales/autocapitalize
---
{{HTMLSidebar("Global_attributes")}}

El {{web.link("/es/docs/Web/HTML/Global_attributes", "atributo global")}} {{HTMLAttrxRef("autocapitalize", "input")}} es un atributo enumerado que controla si la entrada de texto se escribe en mayúsculas automáticamente a medida que el usuario la introduce/edita. El atributo debe tomar uno de los siguientes valores:

- `off` o `none`, no se aplica capitalización automática (todas las letras están predeterminadas en minúsculas)
- `on` o `sentences`, la primera letra de cada oración de manera predeterminada tiene una letra mayúscula; todas las demás letras están predeterminadas en minúsculas
- `words`, la primera letra de cada palabra de manera predeterminada tiene una letra mayúscula; todas las demás letras están predeterminadas en minúsculas
- `characters`, todas las letras de manera predeterminada deben estar en mayúsculas

El atributo {{HTMLAttrDef("autocapitalize")}} no afecta el comportamiento al escribir en un teclado físico. En cambio, afecta el comportamiento de otros mecanismos de entrada, como teclados virtuales en dispositivos móviles y entrada de voz. El comportamiento de tales mecanismos es que a menudo ayudan a los usuarios escribiendo en mayúscula automáticamente la primera letra de las oraciones. El atributo {{HTMLAttrDef("autocapitalize")}} permite a los autores redefinir ese comportamiento por elemento.

El atributo {{HTMLAttrDef("autocapitalize")}} nunca hace que se habilite la autocapitalización para un elemento {{HTMLElement("input")}} con un atributo {{HTMLAttrxRef("type", "input")}} cuyo valor es {{HTMLAttrDef("url")}}, {{HTMLAttrDef("email")}} o {{HTMLAttrDef("password")}}.

## Especificaciones

| Especificación                                                                                                   | Estado                               | Comentario |
| ---------------------------------------------------------------------------------------------------------------- | ------------------------------------ | ---------- |
| {{SpecName('HTML WHATWG', "interaction.html#autocapitalization", "autocapitalize")}} | {{ Spec2('HTML WHATWG') }} |            |

## Compatibilidad del navegador

{{Compat("html.global_attributes.autocapitalize")}}
