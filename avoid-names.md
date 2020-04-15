## Avoid Names

- None meaningful names

##### BAD
```JavaScript
function a(x, y) {
  return x + y
}
```

##### GOOD
```JavaScript
function add(first, second) {
  // our body does adding the first and second parameters.
  return first + second
}
```

what is being done inside the method body must be the method name.
