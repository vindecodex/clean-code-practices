## Naming Parameters

##### Basic Rule in naming parameters is similar with variables

Prefer using singular noun for primitive types or object instances

- [x] `function get_name(name)`

Use plural nouns for collections or arrays

- [x] `function print_students(studends)`

##### :no_entry_sign: Avoid verbs as parameter name even if your passing function as parameter, it may confuse your method names.

:x:

```JavaScript
function get_total(firstNumber, secondNumber, add) {
  return add(firstNumber, secondNumber)
}

function add(firstNumber, secondNumber) {
  return firstNumber + secondNumber
}
```

> :gem: Instead convert it into nouns

:white_check_mark:

```JavaScript
function get_total(firstNumber, secondNumber, sum) {
  return sum(firstNumber, secondNumber)
}

function add(firstNumber, secondNumber) {
  return firstNumber + secondNumber
}
```

> :gem: rules in naming variables also applies in parameters


[:arrow_left: Naming Variables](/variable-names.md) | [:arrow_right: ](/.md)
