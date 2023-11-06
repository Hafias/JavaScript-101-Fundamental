### 🟢 And Table
|P|Q|P AND Q|
|:-:|:-:|:-:|
|T|T|T|
|T|F|F|
|F|T|F|
|F|F|F|



### 🟢 Or Table
|P|Q|P OR Q|
|:-:|:-:|:-:|
|T|T|T|
|T|F|T|
|F|T|T|
|F|F|F|



### 🟢 Not Table
|P|NOT P|
|:-:|:-:|
|T|F|
|F|T|



### 🟢 Example
```JavaScript
// And
const P = true;
const Q = false;

const howToAnd = P && Q;
```
```JavaScript
// Or
const P = true;
const Q = false;

const howToOr = P || Q;
```
```JavaScript
// Not
const P = true;

const howToNot = !P;
```