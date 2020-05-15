# disallow the `Object.getOwnPropertySymbols` method (es/no-object-getownpropertysymbols)

This rule reports ES2015 `Object.getOwnPropertySymbols` method as errors.

## Examples

⛔ Examples of **incorrect** code for this rule:

<eslint-playground type="bad" code="/*eslint es/no-object-getownpropertysymbols: error */
const symbols = Object.getOwnPropertySymbols(obj)
" />

## 📚 References

- [Rule source](https://github.com/mysticatea/eslint-plugin-es/blob/v3.0.1/lib/rules/no-object-getownpropertysymbols.js)
- [Test source](https://github.com/mysticatea/eslint-plugin-es/blob/v3.0.1/tests/lib/rules/no-object-getownpropertysymbols.js)
