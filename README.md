# 7-kui-in-codewars

It's so good to get next level in codewars. The show must go on! 


JavaScript:
const first = [1,2,3];
const second = [4,5,6];
const third = [7,8,9];
const fourth = [10,11,12]
let i = 0;
const quarterOf = (month) => {

for (i in first) {
  if (first.includes(month)) {
    return 1
  } else if (second.includes(month)){
    return 2
  } else if (third.includes(month)) {
    return 3
  } else if (fourth.includes(month)) {
    return 4
  }
}
  
}



2 hours agoRefactorDiscuss
8 kyu
Simple multiplication
JavaScript:
function simpleMultiplication(n) {
    return n * (n % 2 ? 9 : 8);
}
22 hours agoRefactorDiscuss
8 kyu
Convert a string to an array
JavaScript:
function stringToArray(string){
  return string.split(' ');
}
yesterdayRefactorDiscuss
7 kyu
Basic Calculator
JavaScript:
function calculate(num1, operation, num2) {
  var ops = {
    '+': function(x, y) { return x + y; },
    '-': function(x, y) { return x - y; },
    '*': function(x, y) { return x * y; },
    '/': function(x, y) { return y === 0 ? null : x / y; }
  };
  return (ops[operation] || function() { return null; })(num1, num2);
}
yesterdayRefactorDiscuss
8 kyu
Opposites Attract
JavaScript:
function lovefunc(flower1, flower2){
 return flower1 % 2 !== flower2 % 2;
}
yesterdayRefactorDiscuss
8 kyu
Are You Playing Banjo?
JavaScript:
function areYouPlayingBanjo(name) {
  return name + (name[0].toLowerCase() == 'r' ? ' plays' : ' does not play') + " banjo";
}
yesterdayRefactorDiscuss
8 kyu
The Feast of Many Beasts
JavaScript:
function feast(beast, dish) {
return beast[0] === dish[0] && beast[beast.length - 1] === dish[dish.length - 1]
}
yesterdayRefactorDiscuss
8 kyu
Grasshopper - Grade book
JavaScript:
function getGrade (s1, s2, s3) {
  avg = (s1+s2+s3)/3;
  if (avg < 60)  return "F";
    else if (avg < 70) return "D";
    else if (avg < 80) return "C";
    else if (avg < 90) return "B";
    else return "A";
}
yesterdayRefactor
8 kyu
DNA to RNA Conversion
JavaScript:
function DNAtoRNA(dna){
  return dna.replace(/T/g, 'U');
}
yesterdayRefactor
8 kyu
Count by X
JavaScript:
function countBy(x, n) {
    var z = [];
    for (i = 1; i <= n; i++) {
        z.push(x * i);
    }
    return z;
}
yesterdayRefactor
8 kyu
Even or Odd
JavaScript:
function evenOrOdd(number) {
  if (number % 2 == 0) {
     return "Even"
  } else {
    
  }
    return "Odd"
}
evenOrOdd(2,7)
yesterdayRefactorDiscuss
8 kyu
Function 1 - hello world
JavaScript:
// Write a function "greet" that returns "hello world!"
function greet() {
  return "hello world!";
}
 greet();

 
yesterdayRefactorDiscuss
8 kyu
Multiply
JavaScript:
function multiply(a, b){
  return a * b
}
multiply(3, 4);
console.log(multiply);
7 days agoRefactor
