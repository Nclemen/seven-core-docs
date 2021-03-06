---
id: svn-number-input
title: number input
---

## Component example

<script type="module" src="https://unpkg.com/@nclemen/seven-core@latest/dist/seven-core/seven-core.esm.js"></script>

### min max example:

```html
<svn-number-input el-id="numberinput" min="2" max="8"></svn-number-input>
```

<svn-number-input el-id="numberinput" min="2" max="8"></svn-number-input>

### disabled example:

```html
<svn-number-input el-id="numberinput" min="2" max="8" disabled></svn-number-input>
```

<svn-number-input el-id="numberinput" min="2" max="8" disabled></svn-number-input>

### readonly example:

```html
<svn-number-input el-id="numberinput" min="2" max="8" readonly></svn-number-input>
```

<svn-number-input el-id="numberinput" min="2" max="8" readonly></svn-number-input>

### step example:

```html
<svn-number-input el-id="numberinput" min="0" max="100" step="10"></svn-number-input>
```

<svn-number-input el-id="numberinput" min="0" max="100" step="10"></svn-number-input>
<!-- Auto Generated Below -->


## Properties

| Property            | Attribute      | Description                                                                        | Type      | Default     |
| ------------------- | -------------- | ---------------------------------------------------------------------------------- | --------- | ----------- |
| `autocomplete`      | `autocomplete` | prop to determine whether or not the autocomplete is turned on for the input field | `boolean` | `false`     |
| `disabled`          | `disabled`     | prop to determine whether or not the input field is disabled or not                | `boolean` | `false`     |
| `elId` _(required)_ | `el-id`        | the id of the number input                                                         | `string`  | `undefined` |
| `list`              | `list`         | a list of possible options that can be chosen from                                 | `any`     | `undefined` |
| `max`               | `max`          | the maximum number of the input field                                              | `number`  | `undefined` |
| `min`               | `min`          | the minimal number of the input field                                              | `number`  | `undefined` |
| `name`              | `name`         | the name of the number input element                                               | `string`  | `undefined` |
| `placeholder`       | `placeholder`  | the placeholder for the number input                                               | `string`  | `undefined` |
| `readonly`          | `readonly`     | prop to determine whether or not the input field is readonly or not                | `boolean` | `false`     |
| `step`              | `step`         | the number step size which is allowed                                              | `number`  | `undefined` |
| `value`             | `value`        | the value of the input field                                                       | `string`  | `undefined` |


----------------------------------------------

*Built with [StencilJS](https://stenciljs.com/)*
