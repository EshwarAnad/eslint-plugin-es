# disallow the `Math.cosh` method (es/no-math-cosh)

This rule reports ES2015 `Math.cosh` method as errors.

## Examples

⛔ Examples of **incorrect** code for this rule:

<eslint-playground type="bad" code="/*eslint es/no-math-cosh: error */
const n = Math.cosh(value)
" />

## 📚 References

- [Rule source](https://github.com/mysticatea/eslint-plugin-es/blob/v3.0.1/lib/rules/no-math-cosh.js)
- [Test source](https://github.com/mysticatea/eslint-plugin-es/blob/v3.0.1/tests/lib/rules/no-math-cosh.js)
