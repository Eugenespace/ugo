 # What is this ?

 Get perfect mathematics 
 
 
 # Installation

 `npm i vovem-ugo --save`
 
 How to use Ugo

```
import Ugo from './node_modules/vovem-ugo/dist/ugo.es.js'

let log = console.log;

const obj = new  Ugo();

// addition
const intValue = [1, 2, 3, [4, 5, [6, 7], 8, 9]]; 
obj.add(obj.flatten(intValue)); // [1,2,3,4,5,6,7,8,9]

//or
// obj.add([2,5,1]) // 8

// sum the integer values
log(`The addition result is: ${obj.sum}`);
log(`The length value is: ${obj.length}`);

// Subtraction
const valueSub = obj.subtract(obj.sum,2);
log(`The subtraction result is: ${valueSub}`);

// Multiplication
const valueMul = obj.multiple(obj.sum,2);
log(`The Multiplication result is: ${valueMul}`);

// Division
const valueDiv = obj.divide(obj.sum,2);
log(`The Division result is: ${valueDiv}`);

```

## Options

* * Additon 
* * Aubtraction
* * Multiplication
* * Division


## NPM Package

```
https://www.npmjs.com/package/vovem-ugo
```
