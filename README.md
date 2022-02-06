# FrontendInterviewQuestions
javascript html css interview questions


[https://medium.com/@kavisha.talsania/angular-development-vs-production-build-671b7fd5dbf4](devVsProdAngular)

[https://www.interviewbit.com/angular-interview-questions/](angular_interview_Q&A)


##Coding questions

(function() { console.log(1); 
setTimeout(function() { console.log(2)}, 1000); 
setTimeout(function() { console.log(3)}, 0); 
console.log(4); })();



function sayHi() { console.log(a); console.log(b); 
var a = ‘varvalnue’; let b = ‘let value’; } 
sayHi();


[...'Jhon']
Jhon


var myObject = { foo: "bar", func: function() 
{ 
var self = this; console.log("outer func: this.foo = " + this.foo); 
console.log("outer func: self.foo = " + self.foo); 
(function() { console.log("inner func: this.foo = " + this.foo); 
console.log("inner func: self.foo = " + self.foo); }()); } 
}; 

myObject.func();





function checkPalandrom(num){
  var splitenumber = num.split();
  var reverseNumbers = [];
  for(var i=o;i<splitenumber.length;i++){
      reverseNumbers.push(splitenumber[i])
  }



}



var list = readHugeList();
 var nextListItem = function() { var item = list.pop(); if (item) { // process the list item... nextListItem(); } };

