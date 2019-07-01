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
````
function booleanToString(b){
  return String (b);
}
https://www.codewars.com/kata/count-the-monkeys/train/javascript
function monkeyCount(n) {
let arr = [];
  for (let i = 1; i <= n; i++){
  arr.push (i);
  }
  return arr;
}
````
https://www.codewars.com/kata/count-odd-numbers-below-n/train/javascript
````
function oddCount(n){
  return Math.floor(n/2);
}
````
https://www.codewars.com/kata/5808dcb8f0ed42ae34000031

````
function switchItUp(number){
  let a = ['Zero', 'One', 'Two', 'Three', 'Four', 'Five','Six','Seven', 'Eight', 'Nine'];
  return a[number];
   
 }
````
https://www.codewars.com/kata/57a84137cf1fa5f9f80000d6
````
function sumR(x) {
  if (x.length === 0){
   return 0;
  } else {
    return x.shift() + sumR(x);
    }
}
````
https://www.codewars.com/kata/5b077ebdaf15be5c7f000077

````
function finalGrade (exam, projects) {
  if ( exam > 90 || projects >10) return 100;
  if ( exam > 75 && projects >=5) return 90;
  if ( exam > 50 && projects >=2) return 75;
  return 0;  
}
````

*Master

https://www.codewars.com/kata/convert-to-binary/train/javascript
````javascript
function toBinary(n){
  return Number(n.toString(2));
}
````
https://www.codewars.com/kata/reversed-sequence/javascript
````
const reverseSeq = n => {
  const arr = [];
  for (let i = n; i > 0; i--){
   arr.push(i);
  }
  return arr;
}
````
