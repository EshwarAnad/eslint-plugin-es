# disallow the `Number.isNaN` method (es/no-number-isnan)

This rule reports ES2015 `Number.isNaN` method as errors.

## Examples

⛔ Examples of **incorrect** code for this rule:

<eslint-playground type="bad" code="/*eslint es/no-number-isnan: error */
const b = Number.isNaN(value)
" />

## 📚 References

- [Rule source](https://github.com/mysticatea/eslint-plugin-es/blob/v3.0.1/lib/rules/no-number-isnan.js)
- [Test source](https://github.com/mysticatea/eslint-plugin-es/blob/v3.0.1/tests/lib/rules/no-number-isnan.js)
