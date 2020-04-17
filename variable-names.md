## Naming Variables

##### Basic Rule in naming variables

Prefer using singular noun for primitive types or object instances

- [x] `name` = "John"
- [x] `caster` = new Caster();

Use plural nouns for collections or arrays

- [x] `names` = ["John","Mario","Felix"]

##### :no_entry_sign: Avoid verbs as variable name it may confuse your method names.

:x: run = false

> :gem: Instead convert it into nouns

- [x] runEnabled = false

##### :no_entry_sign: Avoid single letter better to spell it out.

:x: g = 99

- [x] grades = 99

Working with acronyms

##### :x: BAD

:x: httpapiclient

:x: HTTPAPIClient

##### :white_check_mark: GOOD

- [x] httpApiClient

> :gem: Separate them using Camel Case


[:arrow_left: Naming Class](/naming-class.md) | [:arrow_right: Variable Names](/variable-names.md)
