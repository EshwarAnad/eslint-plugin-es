# disallow the `Number.isSafeInteger` method (es/no-number-issafeinteger)

This rule reports ES2015 `Number.isSafeInteger` method as errors.

## Examples

⛔ Examples of **incorrect** code for this rule:

<eslint-playground type="bad" code="/*eslint es/no-number-issafeinteger: error */
const b = Number.isSafeInteger(value)
" />

## 📚 References

- [Rule source](https://github.com/mysticatea/eslint-plugin-es/blob/v3.0.1/lib/rules/no-number-issafeinteger.js)
- [Test source](https://github.com/mysticatea/eslint-plugin-es/blob/v3.0.1/tests/lib/rules/no-number-issafeinteger.js)
