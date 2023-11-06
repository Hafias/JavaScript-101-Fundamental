### 🟢 Syntax
```JavaScript
// out block
{ // <- open block
    // in block
} // <- close block
```



### 🟢 Example (Pass)
```JavaScript
var var1 = "boop ";
{
    var var2 = "beeps";
}
console.log(var1, var2);
```



### 🟢 Example (Fail)
```JavaScript
let var1 = "boop ";
{
    let var2 = "beeps";
}
console.log(var1, var2); // <- var2 is not defined
```



### 🟢 Example (Pass)
```JavaScript
let var1 = "boop ";
{
    let var2 = "beeps";
    console.log(var1, var2);
}
```