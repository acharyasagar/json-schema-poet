# json-schema-poet

[JSON Schema](https://json-schema.org) is a useful way to define input and output schemas.

Typescript is a useful way to verify the types of JavaScript objects.

`json-schema-strictly-poet` Write JSON Schema like you'd write poetry.

## Installation

[JSON Schema](https://json-schema.org) can be installed as a package from ***npm registry***.

```
  npm install --save json-schema-poet
```

## Example

```typescript
import * as jsp from "json-schema-poet";

test("integer yields number schema", () => {
  expect(jsp.integer()).toEqual({ type: "integer" });
});
```

## API

Here are all of the functions in the API.

* `nul()`
* `cnst()`
* `integer()`
* `number()`
* `string()`
* `stringEnum()`
* `numberEnum()`
* `integerEnum()`
* `regex()`
* `boolean()`
* `array()`
* `tuple()`
* `allOf()`
* `anyOf()`
* `oneOf()`
* `not()`
* `dictionary()`
* `type()`
* `object()`
* `extend()`

## Todo

There is plenty of stuff that is not implemented yet.  I'd really appreciate your help!

