## :no_entry_sign: Avoid Names

- None meaningful names

##### :x: BAD
```JavaScript
function a(x, y) {
  return x + y
}
```

##### :white_check_mark: GOOD
```JavaScript
function add(first, second) {
  // our body does add the first and second parameters.
  return first + second
}
```

what is being done inside the method body must be the method name.

---

- Abbreviation Names

#### :x: BAD
```JavaScript
const students = [
  "James",
  "Arturo",
  "Denver"
];

for(let i = 0; i < students.length; i++) {
  let s = students[i]
}
```

#### :white_check_mark: GOOD
```JavaScript
const students = [
  "James",
  "Arturo",
  "Denver"
];

for(let index = 0; index < students.length; index++) {
  let student = students[index]
}
```

---

- Two Word Acronyms

#### :x: BAD
```JavaScript
class HTTPAPIClient {
  // TODO ...
}
```

#### :white_check_mark: GOOD
```JavaScript
class HttpApiClient {
  // TODO ...
}
```

---
[Naming Class :arrow_right:](/naming-class.md)
