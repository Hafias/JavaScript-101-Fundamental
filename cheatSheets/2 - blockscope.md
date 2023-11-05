### 🟢 Syntax
```JavaScript
// out block
{ // <- open block
    // in block
} // <- close block
```



### 🟢 Example (Pass)
```JavaScript
var var1 = "Here ";
{
    var var2 = "we GOOO!";
}
console.log(var1, var2);
```



### 🟢 Example (Fail)
```JavaScript
let var1 = "Here ";
{
    let var2 = "we GOOO!";
}
console.log(var1, var2); // <- var2 is not defined
```



### 🟢 Example (Pass)
```JavaScript
let var1 = "Here ";
{
    let var2 = "we GOOO!";
    console.log(var1, var2);
}
```