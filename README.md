https://www.codewars.com/kata/remove-first-and-last-character/train/javascript
````
function removeChar(str){
 let str1= '';
  for (let i = 1; i < str.length-1; i ++) {
   str1 += str[i];
 }
 return str1;
};
