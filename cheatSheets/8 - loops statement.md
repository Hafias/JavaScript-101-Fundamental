## 🟢 For Loop
### 💲 Syntax
```JavaScript
for (/* initialization */; /* condition */; /* afterthought */) {
  // statement
}

// initialization -> เริ่มต้นที่เท่าไหร่
// condition -> จะทำต่อไปหรือไม่
// afterthought -> หลังจากนั้น initialization จะมีการเพิ่มขึ้นอย่างไร

// continue -> loop รอบถัดไปเลย
// break -> หยุดการ loop
```
### ⚡ Example 1
```JavaScript
// ส่วนใหญ่จะใช้ i กันเป็นสากล
for (let i = 0; i < 5; i++) {
  console.log(i);
}
```
### 🟰 Output 1
```bash
0
1
2
3
4
```
### ⚡ Example 2
```JavaScript
for (let i = 0; i < 5; i = i + 2) {
  console.log(i);
}
```
### 🟰 Output 2
```bash
0
2
4
```
### ⚡ Example 3
```JavaScript
let start = 3;
let end = 5;
for (start; start <= end; start++) {
  console.log(start);
}
```
### 🟰 Output 3
```bash
3
4
5
```
### ⚡ Example 4
```JavaScript
for (let i = 0; i < 5; i++) {
  if ((i == 3) || (i > 3)) {
    continue;
  }

  console.log(i);
}
```
### 🟰 Output 4
```bash
0
1
2
```
### ⚡ Example 5
```JavaScript
for (let i = 0; i < 5; i++) {
  if (i == 3) {
    break;
  }

  console.log(i);
}
```
### 🟰 Output 5
```bash
0
1
2
```



## 🟢 Do-while Loop
### 💲 Syntax
```JavaScript
do {
  // statement
} while (/* condition */);

// condition -> จะทำต่อไปหรือไม่

// continue -> loop รอบถัดไปเลย
// break -> หยุดการ loop
```
### ⚡ Example 1
```JavaScript
let counter = 0;
do {
  console.log(counter);
  counter++;
} while (counter < 5);
```
### 🟰 Output 1
```bash
0
1
2
3
4
```
### ⚡ Example 2
```JavaScript
let counter = 0;
do {
  console.log(counter);
  counter = counter + 2;
} while (counter < 5);
```
### 🟰 Output 2
```bash
0
2
4
```
### ⚡ Example 3
```JavaScript
let start = 3;
let end = 5;
do {
  console.log(start);
  start++;
} while (start <= end);
```
### 🟰 Output 3
```bash
3
4
5
```
### ⚡ Example 4
```JavaScript
let counter = 0;
do {
  if ((counter == 3) || (counter > 3)) {
    counter++;
    continue;
  }
  
  console.log(counter);
  counter++;
} while (counter < 5);
```
### 🟰 Output 4
```bash
0
1
2
```
### ⚡ Example 5
```JavaScript
let counter = 0;
do {
  if (counter == 3) {
    break;
  }
  
  console.log(counter);
  counter++;
} while (counter < 5);
```
### 🟰 Output 5
```bash
0
1
2
```



## 🟢  While-do Loop
### 💲 Syntax
```JavaScript
while (/* condition */) {
  // statement
};

// condition -> จะทำต่อไปหรือไม่

// continue -> loop รอบถัดไปเลย
// break -> หยุดการ loop
```
### ⚡ Example 1
```JavaScript
let counter = 0;
while (counter < 5) {
  console.log(counter);
  counter++;
};
```
### 🟰 Output 1
```bash
0
1
2
3
4
```
### ⚡ Example 2
```JavaScript
let counter = 0;
while (counter < 5) {
  console.log(counter);
  counter = counter + 2;
};
```
### 🟰 Output 2
```bash
0
2
4
```
### ⚡ Example 3
```JavaScript
let start = 3;
let end = 5;
while (start <= end) {
  console.log(start);
  start++;
};
```
### 🟰 Output 3
```bash
3
4
5
```
### ⚡ Example 4
```JavaScript
let counter = 0;
while (counter < 5) {
  if ((counter == 3) || (counter > 3)) {
    counter++;
    continue;
  }
  
  console.log(counter);
  counter++;
};
```
### 🟰 Output 4
```bash
0
1
2
```
### ⚡ Example 5
```JavaScript
let counter = 0;
while (counter < 5) {
  if (counter == 3) {
    break;
  }
  
  console.log(counter);
  counter++;
};
```
### 🟰 Output 5
```bash
0
1
2
```