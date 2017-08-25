# @mapbox/query-selector-contains-element

Check whether a DOM node is contained by any other node on the page matching a selector.

## Installation

```
npm install @mapbox/query-selector-contains-element
```

## API

### querySelectorContainsElement

`querySelectorContainsElement(selector: string, node: Node): boolean`

Returns `true` if any of the node's ancestors match the `selector` (a CSS selector suitable for [`document.querySelectorAll()`](https://developer.mozilla.org/en-US/docs/Web/API/Document/querySelectorAll)).
Otherwise, returns `false`.
