## :no_entry_sign: Avoid Names

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
  // our body does add the first and second parameters.
  return first + second
}
```

what is being done inside the method body must be the method name.

---

- Abbreviation Names

#### BAD
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

#### GOOD
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

#### BAD
```JavaScript
class HTTPAPIClient {
  // TODO ...
}
```

#### GOOD
```JavaScript
class HttpApiClient {
  // TODO ...
}
```

---
