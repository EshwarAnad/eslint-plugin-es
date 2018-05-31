# disallow the `Math.clz32` method (es/no-math-clz32)

This rule reports ES2015 `Math.clz32` method as errors.

## Examples

⛔ Examples of **incorrect** code for this rule:

```js
const n = Math.clz32(value)
```

## 📚 References

- [Rule source](https://github.com/mysticatea/eslint-plugin-es/blob/v1.2.0/lib/rules/no-math-clz32.js)
- [Test source](https://github.com/mysticatea/eslint-plugin-es/blob/v1.2.0/tests/lib/rules/no-math-clz32.js)