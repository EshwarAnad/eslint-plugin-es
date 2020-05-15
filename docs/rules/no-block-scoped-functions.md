# disallow block-scoped function declarations (es/no-block-scoped-functions)

This rule reports ES2015 block-scoped function declarations as errors.

## Examples

⛔ Examples of **incorrect** code for this rule:

<eslint-playground type="bad" code="/*eslint es/no-block-scoped-functions: error */
if (a) {
    function f() {}
} else {
    function g() {}
}
" />

## 📚 References

- [Rule source](https://github.com/mysticatea/eslint-plugin-es/blob/v3.0.1/lib/rules/no-block-scoped-functions.js)
- [Test source](https://github.com/mysticatea/eslint-plugin-es/blob/v3.0.1/tests/lib/rules/no-block-scoped-functions.js)
