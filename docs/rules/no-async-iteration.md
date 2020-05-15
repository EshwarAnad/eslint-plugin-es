# disallow async iteration (es/no-async-iteration)

This rule reports ES2018 [async iteration](https://github.com/tc39/proposal-async-iteration#readme) as errors.

## Examples

⛔ Examples of **incorrect** code for this rule:

<eslint-playground type="bad" code="/*eslint es/no-async-iteration: error */
async function* f1() {}
let f2 = async function*() {}
let obj = { async* f4() {} }
class A { async* f5() {} }

async function wrap() {
    for await (const x of xs) {}
}
" />

## 📚 References

- [Rule source](https://github.com/mysticatea/eslint-plugin-es/blob/v3.0.1/lib/rules/no-async-iteration.js)
- [Test source](https://github.com/mysticatea/eslint-plugin-es/blob/v3.0.1/tests/lib/rules/no-async-iteration.js)
