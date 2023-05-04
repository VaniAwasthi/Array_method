# Array_method :computer:
## 1. Concat Method.
### Example.

```js
// single argument
console.log(numbers.concat(characters));
// multiple argument
console.log(numbers.concat(characters, booleans));

```
 
<details><summary>Solution</summary>
 
```js
 
  const num1 = [1, 2, 3];
    const num2 = [4, 5, 6];
    const num3 = [7, 8, 9];
    document.write(num1.concat(num2) + "<br>"); // single argument
    document.write(num1.concat(num2, num3) + "<br>"); // multiple argument
```
 </details> 
<details><summary>Result</summary>
 
```js
 [1,2,3,"a","b","c"]
[1,2,3,"a","b","c",true,false]
  
```
 </details> 

## 2. copyWithIn Method.
### Example.

```js
console.log(arr1.copyWithin(2));
```
 
<details><summary>Solution</summary>
 
```js
 
const arr1 = ['a', 'b', 'c', 'd', 'e', 1, 2, 3];
const arr2 = ['a', 'b', 'c', 'd', 'e', 1, 2, 3];
const arr3 = ['a', 'b', 'c', 'd', 'e', 1, 2, 3];

// copy elements from index 0 to last index to index 2
console.log(arr1.copyWithin(2));
// copy elements from index 4 to last index to index 2
console.log(arr2.copyWithin(2, 4));
```
 </details> 
<details><summary>Result</summary>
 
```js
["a","b","a","b","c","d","e",1]
["a","b","e",1,2,3,2,3]
  
```
 </details> 
 
## 3. entries Method.
### Example
```js 
console.log(iterator1.next());
```
<details><summary>Solution</summary>
 
```js
const arr = ["a", "b", "c", "d", "e"];
const iterator1 = arr.entries();
console.log(iterator1.next());
console.log(iterator1.next().value);
console.log(iterator1.next().value);

```
 </details> 
<details><summary>Result</summary>
 
```js
{"value":[0,"a"],"done":false}
[1,"b"]
[2,"c"]
  
```
 </details> 
