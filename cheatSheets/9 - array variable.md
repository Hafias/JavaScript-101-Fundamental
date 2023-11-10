## 🟢 Array Variable
### 💲 Syntax
```
[instruction] [name] = [[value 0], [value 1], [value 2], ... ,[value n]]

value -> number | string | boolean | array | object | function
```



### ⚡ Example Value
```JavaScript
const thisIsEmptyArray = [];
const thisIsArrayOfNumber = [1, 9, 9, 7, 3, 5, 0, -8];
const thisIsArrayOfString = ["MyName", "is", "Array", "Hell", "Yeah"];
const thisIsArrayOfBool = [true, true, false];

const mixArray = [1, 9, 9, "MyName", false];
```



### 🔢 index
```
index บอกถึงตำแหน่งว่า ข้อมูลนั้นๆ อยู่ในตำแหน่งที่เท่าไหร่ โดยที่เริ่มจาก 0 เสมอ

const arrayVariable = [1, 9, 9, ..., n];
                       |  |  |       |
index 0 ----------------  |  |       |
index 1 -------------------  |       |
index 2 ----------------------       |
index n ------------------------------
```



### 🌱 Value Assignment
```JavaScript
let newArrayVar = [];
newArrayVar[0] = "new value"; // assign value แบบระบุ index
newArrayVar.push("new value"); // assign value แบบเพิ่มเข้าไปตรงๆ (จะต่อที่ index สุดท้ายเสมอ)

const preConArray1 = [0, 1, 2, 3];
const preConArray2 = [4, 5, 6, 7];
const conArray1 = preConArray1.concat(preConArray2);
const conArray2 = [...preConArray1, ...preConArray2];
```



### 🌳 Value Accessibility 1
```JavaScript
const myArray = [1, 9, 9, 7, 3, 5, 0, -8];

// asscess all value
console.log(myArray);
```
### 🍏 Output 1
```bash
[ <- ของ myArray
  1, 9, 9,  7,
  3, 5, 0, -8
]
7 <- ของ indexValue
```
### 🌳 Value Accessibility 2
```JavaScript
const myArray = [1, 9, 9, 7, 3, 5, 0, -8];

// access value by index
const indexValue = myArray[3];
console.log(indexValue);
```
### 🍏 Output 2
```bash
[ <- ของ myArray
  1, 9, 9,  7,
  3, 5, 0, -8
]
7 <- ของ indexValue
```