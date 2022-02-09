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
 
 
 
 var a = [1,2,3,6,8,9];
var b = [3,6]
var i = 0;

while(i>=0 && i<a.length-1){

  var findValue = [a[i],a[i+1]];
  console.log("finded values:",findValue);
  if(JSON.stringify(findValue) === JSON.stringify(b)){
     console.log("arrays are matched"+" "+ "finded value:",findValue + "given value:",b);
     i=a.length-1;
  }else{
    i++
  }



var obj1 = { valueOfThis: function(){ return this; } }
 var obj2 = { valueOfThis: ()=>{ return this; } } 
 console.log(obj1.valueOfThis()); 
 console.log(obj2.valueOfThis()) 



 (function timer() { 
     for (var i=0; i<=5; i++) { 
         setTimeout(function clog() {console.log(i)}, i*1000); 
        } 
    })();



let opration = BheaverSubject<>()

opration.then()
         .then(value)


    .mainDiv{
        display:flex;
        flex-flow:center;
    }
    
    
    
    #angular state management
    #observables rxjs
    #cloud based questions
    #data bases
    
