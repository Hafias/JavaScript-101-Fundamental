### 🟢 Syntax
```
[variable] [assignment operator] [value]
[variable] [assignment operator] [variable]
[variable] [assignment operator] [value] [arithmetic operator] [variable]
[variable] [assignment operator] [variable] [arithmetic operator] [variable]
[variable] [assignment operator] [variable] [arithmetic operator] [value]
```


### 🟢 Arithmetic Operators
  - = (equal)
  - += (plus equal)
  - -= (minus equal)
  - *= (multiply equal)
  - /= (divide equal)
  - %= (modulus equal)
  - **= (exponentiation equal)



### 🟢 Use in case
กรณีที่ต้องการให้ตัวแปลเดิม แต่ทำการเพิ่ม ลบ ค่าเข้าไป หรือกระทำการกับค่าเดิม

### 🟢 Example
```JavaScript
const var1 = 3;
let var2 = 6;
var2 += var1; // now, var2 is 9
```
```JavaScript
const var1 = 3;
const var2 = 6;
let var3 = 5;
var3 *= (var2 / var1) // now, var2 is 10
```