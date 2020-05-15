# disallow reserved words as property names (es/no-keyword-properties)

This rule reports ES5 reserved words as property names as errors.

## Examples

⛔ Examples of **incorrect** code for this rule:

<eslint-playground type="bad" code="/*eslint es/no-keyword-properties: error */
var a = { if: 1, class: 2 }
a.if = 2
a.class = 3
" />

## 📚 References

- [Rule source](https://github.com/mysticatea/eslint-plugin-es/blob/v3.0.1/lib/rules/no-keyword-properties.js)
- [Test source](https://github.com/mysticatea/eslint-plugin-es/blob/v3.0.1/tests/lib/rules/no-keyword-properties.js)
