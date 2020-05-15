# disallow destructuring (es/no-destructuring)

This rule reports ES2015 destructuring assignments/bindings as errors.

## Examples

⛔ Examples of **incorrect** code for this rule:

<eslint-playground type="bad" code="/*eslint es/no-destructuring: error */
let [a, b] = array
let {c, d} = obj
function f({a, b}, [c, d]) {}

;[a, b] = array
;({c, d} = obj)
" />

## 📚 References

- [Rule source](https://github.com/mysticatea/eslint-plugin-es/blob/v3.0.1/lib/rules/no-destructuring.js)
- [Test source](https://github.com/mysticatea/eslint-plugin-es/blob/v3.0.1/tests/lib/rules/no-destructuring.js)
