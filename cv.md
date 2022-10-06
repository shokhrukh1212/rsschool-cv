# Shokhrukh Karimov

***

### Contact information:

**Phone:** +998 91 426 20 25<br>
**E-mail:** [shokhrukh@gmail.com](shokhrukhkarimovme@gmail.com)<br>
**GitHub:** [shokhrukhGit](https://github.com/shokhrukh1212)<br>
**Telegram:**[shokhrukhTelegram](https://t.me/khon_engineer)<br>

***

### About

I am a graduate student at Tashkent University of Information technology, Urgench brench, in Uzbekistan. 
I am interested in Math, algorithms, English and my major is Software Engineering. 

***

### Skills:

Languages: JavaScript, HTML5, CSS3, C++, Python<br>
Frameworks: Vue.js<br>
Soft skills: Git Hub<br>


***

### Code example

[Are 'they' the same](https://www.codewars.com/kata/550498447451fbbd7600041c)

```
function comp(array1, array2){
  if(array1 === null || array2 === null) { return false; }
  if(array1.length !== array2.length) { return false; }
  let subArray1 = array1.map(e => { return e*e; }).sort(function(a, b) { return a-b; }); 
  let subArray2 = array2.map(e => { return e*e; }).sort(function(a, b) { return a-b; });
  
  array1.sort(function(a, b) { return a-b; });
  array2.sort(function(a, b) { return a-b; });
  
  return (JSON.stringify(array1) == JSON.stringify(subArray2) || JSON.stringify(array2) == JSON.stringify(subArray1)) ? true : false;
  
}

```

***

### Education

[Tashkent University of Information technology](https://www.ubtuit.uz/)<br>
Major: Software Engineering<br>
Year: Graduate student<br>

***

### Experience


[cs50](https://www.edx.org/course/cs50s-web-programming-with-python-and-javascript): CS50's Computer science course<br>
[FreeCodeCamp](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/): JavaScript Algorithms and Data Structures<br>

***

### English

Level: B2<br>
Certificate: Ielts 6.5
