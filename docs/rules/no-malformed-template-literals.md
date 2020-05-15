# disallow template literals with invalid escape sequences (es/no-malformed-template-literals)

This rule reports ES2018 [template literals with invalid escape sequences](https://github.com/tc39/proposal-template-literal-revision#readme) as errors.

## Examples

⛔ Examples of **incorrect** code for this rule:

<eslint-playground type="bad" code="/*eslint es/no-malformed-template-literals: error */
tag`\unicode`
" />

## 📚 References

- [Rule source](https://github.com/mysticatea/eslint-plugin-es/blob/v3.0.1/lib/rules/no-malformed-template-literals.js)
- [Test source](https://github.com/mysticatea/eslint-plugin-es/blob/v3.0.1/tests/lib/rules/no-malformed-template-literals.js)
