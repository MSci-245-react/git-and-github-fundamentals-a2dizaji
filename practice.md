# Lab 1 Practice

One thing I learned from Lecture 1. is that JavaScript can produce surprising results because values have types and some operations use implicit coercion. Testing small expressions in the Node REPL makes it easier to see the actual behavior instead of guessing.

- JavaScript has primitive types such as `number`, `string`, and `boolean`.
- The `typeof` operator reports the type of a value.
- Some equality checks can coerce values before comparing them.

```javascript
0.1 + 0.2
typeof null
[] == false
`2 + 3 = ${2 + 3}`
```

```
0.30000000000000004
'object'
true
'2 + 3 = 5'
```
