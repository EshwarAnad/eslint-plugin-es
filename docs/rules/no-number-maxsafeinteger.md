# disallow the `Number.MAX_SAFE_INTEGER` property (es/no-number-maxsafeinteger)

This rule reports ES2015 `Number.MAX_SAFE_INTEGER` property as errors.

## Examples

⛔ Examples of **incorrect** code for this rule:

<eslint-playground type="bad" code="/*eslint es/no-number-maxsafeinteger: error */
const b = Number.MAX_SAFE_INTEGER
" />

## 📚 References

- [Rule source](https://github.com/mysticatea/eslint-plugin-es/blob/v3.0.1/lib/rules/no-number-maxsafeinteger.js)
- [Test source](https://github.com/mysticatea/eslint-plugin-es/blob/v3.0.1/tests/lib/rules/no-number-maxsafeinteger.js)
