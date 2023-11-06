### 🟢 Syntax
```
[variable] = [value] [arithmetic operator] [value]
[variable] = [value] [arithmetic operator] [variable]
[variable] = [variable] [arithmetic operator] [variable]
[variable] = [variable] [arithmetic operator] [value]
```


### 🟢 Arithmetic Operators
  - \+ (plus)
  - \- (minus)
  - \* (multiply)
  - / (divide)
  - % (modulus)
  - ++ (increment)
  - -- (decrement)
  - ** (exponentiation)



### 🟢 Example
```JavaScript
const var1 = 7;
const var2 = 6;
const var3 = var1 + var2;
```
```JavaScript
const var1 = 7;
const var2 = var1 + 6;
```
```JavaScript
const var1 = 7 + 6;
```
```JavaScript
const var1 = "boop";
const var2 = "beep";
const var3 = var1 + " " + var2; // "boop beep"
```
```JavaScript
let var1 = 23;
var1++;
// var1 -> 24
```
```JavaScript
let var1 = 23;
let var2 = var1++;
// var1 -> 24
// var2 -> 23
// เพราะ.. โปรแกรมทำงาน ซ้ายไปขวา ทำให้ var2 = var1 ก่อนที่จะ + 1 ให้กับ var2
```