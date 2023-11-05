### 🟢 Syntax
```
instruction name = value
```



### 🟢 Instruction
|Type|Scope|Re-Declare|Re-Assign|
|-|:-:|:-:|:-:|
|var|global|✔️|✔️|
|let|block|❌|✔️|
|const|block|❌|❌|



### 🟢 Naming Style Guide
#### Camel case
  - carmelCase
  - myFirstVariable
  - thisIsSecondVar
  - myHappiness
  - workFlow
  - preResponse
  - somethingWork
#### Pascal case
  - CarmelCase
  - MyFirstVariable
  - ThisIsSecondVar
  - MyHappiness
  - WorkFlow
  - PreResponse
  - SomethingWork
#### Snake case
  - carmel_case
  - my_first_variable
  - this_is_second_var
  - my_happiness
  - work_flow
  - pre_response
  - something_work
#### Upper Snake case
  - CARMEL_CASE
  - MY_FIRST_VARIABLE
  - THIS_IS_SECOND_VAR
  - MY_HAPPINESS
  - WORL_FLOW
  - PRE_RESPONSE
  - SOMETHING_WORK



### 🟢 Naming Rule
  - start with letter, _ or $
  - cannot contain space or special charactor
  - cannot to be same as reserved word
  - valid only letter, number, _ or $



### 🟢 Reserved Words (not all)
  - recommend to remember
    - await
    - break
    - case
    - catch
    - default
    - delete
    - do
    - else
    - export
    - false
    - for
    - if
    - let
    - new
    - null
    - return
    - switch
    - this
    - true
    - try
    - var
    - while
    - Date
    - number
    - Number
    - string
    - String
  - good to know
    - abstract
    - extends
    - implements
    - import
    - private
    - protected
    - public
    - static
    - super
    - throw
    - void
    - Array
    - Math
    - Object
    - undefined
  - if forget it program will tell
    - boolean
    - debugger
    - enum
    - funal
    - function
    - goto
    - double
    - float
    - int
    - short
    - typeof
    - NaN
    - isNaN
    - toString
    - valueOf
    - typeOf



### 🟢 Variable Type
#### Number
  - 1
  - 9
  - 7
#### String
  - "1" <- double qoute
  - '9' <- single qoute
  - \`7\` <- grave accent or backtick
  - "boop beep boop beep"
#### Boolean
  - true
  - false
  - 0 <- imply to false
  - number except 0 <- imply to true
#### Array
  - [1, 9, 7, 3, 5]
#### Object
```json
{
  "key1": 1,
  "key2": "beep beep beeps beeppsss!",
  "key3": true,
  "key4": [true, false, 6, 3, "beeps"],
}
```