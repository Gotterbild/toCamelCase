# toCamelCase

Fast transform of a string to camelCase. Removes spaces, dashes and underscores.

```js
import toCamelCase from './gtb.tocamelcase'

toCamelCase('Some string') // someString
toCamelCase('some-string') // someString
toCamelCase('SOME_STRING') // someString
toCamelCase('some--WEIRD__string') // someWeirdString
```