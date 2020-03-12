# Radio

```html preview
<sl-radio name="test">Default</sl-radio><br><br>
<sl-radio name="test"checked>Checked</sl-radio><br><br>
<sl-radio name="test"disabled>Disabled</sl-radio><br><br>
```

<!-- Auto Generated Below -->


## Properties

| Property         | Attribute         | Description                                       | Type      | Default     |
| ---------------- | ----------------- | ------------------------------------------------- | --------- | ----------- |
| `checked`        | `checked`         | Set to true to draw the radio in a checked state. | `boolean` | `false`     |
| `disabled`       | `disabled`        | Set to true to disable the radio.                 | `boolean` | `false`     |
| `name`           | `name`            | A native input's name attribute.                  | `string`  | `undefined` |
| `nativeTabindex` | `native-tabindex` | The radio's tabindex attribute.                   | `number`  | `undefined` |
| `value`          | `value`           | The native input's value attribute.               | `string`  | `undefined` |


## Methods

### `removeFocus() => Promise<void>`

Removes focus from the radio.

#### Returns

Type: `Promise<void>`



### `setFocus() => Promise<void>`

Sets focus on the radio.

#### Returns

Type: `Promise<void>`




## Slots

| Slot | Description        |
| ---- | ------------------ |
|      | The radio's label. |


----------------------------------------------

