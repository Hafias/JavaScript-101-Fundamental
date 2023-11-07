## 🟢 If Statement
### 💲 Syntax
```JavaScript
if (/* condition */) {
  // if condition is true
  // statement
}
```
### ⚡ Example
```JavaScript
const var1 = 70;
const var2 = 60;
if (var1 > var2) {
  console.log(var1, " greater than ", var2);
}
console.log("DONE");
```



## 🟢 If-else Statement
```JavaScript
if (/* condition */) {
  // if condition is true
  // statement
}
else {
  // if condition is false
  // statement
}
```
### ⚡ Example
```JavaScript
const var1 = 70;
const var2 = 60;
if (var1 > var2) {
  console.log(var1, " greater than ", var2);
}
else {
  console.log(var1, " less than ", var2);
}
console.log("DONE");
```



## 🟢 If-else-if Statement
```JavaScript
if (/* condition */) {
  // statement
}
else if {
  // statement
}
```
```JavaScript
if (/* condition */) {
  // statement
}
else if {
  // statement
}
else {

}
```
### ⚡ Example
```JavaScript
const myVar = 70;
if (myVar > 80) {
  console.log(myVar, " greater than ", 80);
}
else if (var2 > 60){
  console.log(myVar, " greater than ", 60);
}
console.log("DONE");
```
```JavaScript
const myVar = 70;
if (myVar > 80) {
  console.log(myVar, " greater than ", 80);
}
else if (var2 > 60){
  console.log(myVar, " greater than ", 60);
}
else {
  console.log(myVar, " less than ", 60);
}
console.log("DONE");
```



## 🟢 Switch Statement
### 💲 Syntax
```JavaScript
switch (/* expression */) {
  case /* expression | statement */: 
    // statement;
  case /* expression | statement */: 
    // statement;
    break;
  case /* expression | statement */: {
    // statement
  }
  case /* expression | statement */: {
    // statement
    break;
  }
  // default is not required
  default: {
    // statement
  }
}
```
### ⚡ Example 1
```JavaScript
const day = 3;
switch (day) {
  case 1: console.log("Sunday");
  case 2: console.log("Monday");
  case 3: console.log("Tuesday");
  case 4: console.log("Wednesday");
  case 5: console.log("Thursday");
  case 6: console.log("Friday");
  case 7: console.log("Saturday");
}
```
### 🟰 Output
```bash
Tuesday
Wednesday
Thursday
Friday
Saturday
```
### ⚡ Example 2
```JavaScript
const day = 3;
switch (day) {
  case 1: console.log("Sunday"); break;
  case 2: console.log("Monday"); break;
  case 3: console.log("Tuesday"); break;
  case 4: console.log("Wednesday"); break;
  case 5: console.log("Thursday"); break;
  case 6: console.log("Friday"); break;
  case 7: console.log("Saturday"); break;
}
```
### 🟰 Output
```bash
Tuesday
```
### ⚡ Example 3
```JavaScript
const day = 3;
switch (true) {
  case day > 1: console.log("Sunday");
  case day > 2: console.log("Monday");
  case day > 3: console.log("Tuesday");
  case day > 4: console.log("Wednesday");
  case day > 5: console.log("Thursday");
  case day > 6: console.log("Friday");
  case day > 7: console.log("Saturday");
}
```
### 🟰 Output
```bash
Sunday
Monday
Tuesday
Wednesday
Thursday
Friday
Saturday
```
### ⚡ Example 4
```JavaScript
const day = 3;
switch (true) {
  case day > 1: console.log("Sunday"); break;
  case day > 2: console.log("Monday"); break;
  case day > 3: console.log("Tuesday"); break;
  case day > 4: console.log("Wednesday"); break;
  case day > 5: console.log("Thursday"); break;
  case day > 6: console.log("Friday"); break;
  case day > 7: console.log("Saturday"); break;
}
```
### 🟰 Output
```bash
Sunday
```
### ⚡ Example 5
```JavaScript

const day = 753;
switch (day) {
  case 1: {
    console.log("Sunday");
    break;
  }
  case 2: {
    console.log("Monday");
    break;
  }
  case 3: {
    console.log("Tuesday");
    break;
  }
  case 4: {
    console.log("Wednesday");
    break;
  }
  case 5: {
    console.log("Thursday");
    break;
  }
  case 6: {
    console.log("Friday");
    break;
  }
  case 7: {
    console.log("Saturday");
    break;
  }
  default: {
    console.log("BOOP BEEPPSSSS!");
    break;
  }
}
```
### 🟰 Output
```bash
BOOP BEEPPSSSS!
```