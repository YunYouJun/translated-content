---
title: HTMLEmbedElement
slug: Web/API/HTMLEmbedElement
---

{{APIRef("HTML DOM")}}

**`HTMLEmbedElement`** インターフェイスは、（継承によって使用できる通常の {{domxref("HTMLElement")}} インターフェイスのものに加えて） {{HTMLElement("embed")}} 要素を操作するための特別なプロパティを提供します。

> **Note:** このトピックでは、標準規格で定義されている `HTMLEmbedElement` インターフェイスについて説明します。それ以前の、標準化されていない版ののインターフェースは扱いません。

{{InheritanceDiagram}}

## プロパティ

_親である {{domxref("HTMLElement")}} からプロパティを継承しています。_

- {{domxref("HTMLEmbedElement.align")}} {{deprecated_inline}}
  - : 列挙型のプロパティを表す文字列で、要素の内容を周囲のコンテキストから見てどう配置するかを示します。指定可能な値は `"left"`, `"right"`, `"center"`, `"justify"` です。
- {{domxref("HTMLEmbedElement.height")}}
  - : 文字列で HTML の {{htmlattrxref("height", "embed")}} 属性を反映しており、リソースが表示される高さが入ります。
- {{domxref("HTMLEmbedElement.name")}} {{deprecated_inline}}
  - : 文字列で、埋め込まれたオブジェクトの名前を表します。
- {{domxref("HTMLEmbedElement.src")}}
  - : 文字列で HTML の {{htmlattrxref("src", "embed")}} 属性を反映しており、リソースの場所が入ります。
- {{domxref("HTMLEmbedElement.type")}}
  - : 文字列で HTML の {{htmlattrxref("type", "embed")}} 属性を反映しており、リソースの型が入ります。
- {{domxref("HTMLEmbedElement.width")}}
  - : 文字列で HTML の {{htmlattrxref("height", "embed")}} 属性を反映しており、リソースが表示される幅が入ります。

## メソッド

_固有のメソッドはありません。親である {{domxref("HTMLElement")}} からメソッドを継承しています。_

## 仕様書

{{Specifications}}

## ブラウザーの互換性

{{Compat}}

## 関連情報

- このインターフェイスを実装している HTML 要素: {{ HTMLElement("embed") }}
