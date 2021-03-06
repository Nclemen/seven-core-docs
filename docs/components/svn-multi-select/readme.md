---
id: svn-multi-select
title: multi select
---

## Component example

<script type="module" src="https://unpkg.com/@nclemen/seven-core@latest/dist/seven-core/seven-core.esm.js"></script>

```html
<svn-multi-select 
  options='[
  {"name":"volvo"},
  {"name":"cheetos"},
  {"name":"lays"},
  {"name":"bill"},
  {"name":"cypher"},
  {"name":"saab","value":"auto s"},
  {"name":"audi","value":"auto"}
  ]'
></svn-multi-select>
```

the code example above will result into this:

<svn-multi-select options='[{"name":"volvo"},{"name":"cheetos"},{"name":"lays"},{"name":"bill"},{"name":"cypher"}, {"name":"saab","value":"auto s"}, {"name":"audi","value":"auto"}]'></svn-multi-select>

<!-- Auto Generated Below -->


## Properties

| Property            | Attribute  | Description                                                    | Type      | Default     |
| ------------------- | ---------- | -------------------------------------------------------------- | --------- | ----------- |
| `elId` _(required)_ | `el-id`    | the id of component                                            | `string`  | `undefined` |
| `multiple`          | `multiple` | value to turn multiple file select on or off                   | `boolean` | `false`     |
| `name`              | `name`     | the name attribute for the select element                      | `string`  | `undefined` |
| `options`           | `options`  | an array of options for the select element with name and value | `any`     | `undefined` |


## Dependencies

### Depends on

- [svn-chip](../svn-chip)

### Graph
```mermaid
graph TD;
  svn-multi-select --> svn-chip
  style svn-multi-select fill:#f9f,stroke:#333,stroke-width:4px
```

----------------------------------------------

*Built with [StencilJS](https://stenciljs.com/)*
