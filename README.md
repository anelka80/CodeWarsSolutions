https://www.codewars.com/kata/remove-first-and-last-character/train/javascript
````
function removeChar(str){
 let str1= '';
  for (let i = 1; i < str.length-1; i ++) {
   str1 += str[i];
 }
 return str1;
};
````

https://www.codewars.com/kata/convert-a-boolean-to-a-string/train/javascript
``````````
function booleanToString(b){
  return String (b);
}
``````
https://www.codewars.com/kata/count-the-monkeys/train/javascript
function monkeyCount(n) {
let arr = [];
  for (let i = 1; i <= n; i++){
  arr.push (i);
  }
  return arr;
}
https://www.codewars.com/kata/count-odd-numbers-below-n/train/javascript
function oddCount(n){
  return Math.floor(n/2);
}