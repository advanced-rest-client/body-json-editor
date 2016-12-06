[![Build Status](https://travis-ci.org/advanced-rest-client/body-json-editor.svg?branch=master)](https://travis-ci.org/advanced-rest-client/body-json-editor)  

# body-json-editor

`<body-json-editor>` A JSON editor for HTTP body

It provides a visual editor for the JSON body.

### Example
```
<body-json-editor value='["apple", 1234]'></body-json-editor>
```

To set / get value on / from the element use the `value` property. Each time
something change in the editor the string `value` will be regenerated.
It is also possible to set a JavaScript objkect on this element using
`json` property but it is immutable and changes will not be reflected to it.

### Styling
`<body-json-editor>` provides the following custom properties and mixins for
styling:

Custom property | Description | Default
----------------|-------------|----------
`--body-json-editor` | Mixin applied to the element | `{}`

