# Validation rules list

# List:
```
- not null, undefined
- trim. has no begging or ending spaces.
- protect the data against the injections (use RegExp.test(value) in JS, htmlspecialchars() in PHP +8.1)
- prevent potentially malicious characters ( use /[<>(){}[\]'";]/.test(value))
```
