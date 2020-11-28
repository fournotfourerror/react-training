# react-training

### Functions
* Static function
 ```javascript
    function subtraction(){
    var i=10;
    var j=20;
    return i-j;
} 
```
* Dynamic functions
```javascript
function multiplication(a,b){
    return a*b;
}

multiplication(10,2)
```

* Anonymous functions
```javascript
var addition=function(a,b){
    return a+b;
}

addition(10,20)
```

* Arrow functions
```javascript
var addition=(a,b)=>{
    return a+b;
}

addition(10,20)
```


### Iterations
* for
* map
  ```javascript
    array1.map(function(value,index){
    console.log(value+"is having this index value "+index)
  })
  
  array1.map((value,index)=>{
    console.log(value+"is having this index value "+index)
  })
  ```
* for-in
```javascript
  for(i in array1){
    console.log(i)
}
```
* for-of
```javascript
    for(i of array1){
    console.log(i)
}
```

* forEach
```javascript
  array1.forEach(i=>{
    console.log(i)
})
```
