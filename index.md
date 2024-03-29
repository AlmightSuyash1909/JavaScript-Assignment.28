#### What will be the output of the following code snippet given below:

1. What does the following code print to the console?

```js
let hat = {
  size: 'large',
  color: 'orange',
};
console.log(hat.size);
```

// Output - "large"

2. What does the following code print to the console?

```js
let hat = {
  size: 'large',
  color: 'orange',
};
console.log(hat['color']);
```

// Output - "orange"

3. What does the following code print to the console?

```js
let hat = {
  size: 'large',
  color: 'orange',
};

hat.color = 'red';
console.log(hat.color);
```
// Output - "red"

4. What does the following code print to the console?

```js
let pen = {};
pen.ink = 'blue';
console.log(pen.ink);
```
// Output - "blue"

5. What does the following code print to the console?

```js
let hat = {
  size: 'large',
  color: 'orange',
};

console.log(hat['cost']);
```

// Output - undefined

6. What does the following code print to the console?

```js
let hat = {
  rating: function () {
    return 'Hat is top rated';
  },
  color: 'green',
};
console.log(hat.rating());
```
// Output -  'Hat is top rated'

8. What does the following code print to the console?

```js
let hat = {
  size: 'medium',
  color: 'green',
  introduction: function () {
    return `The size of hat is ${hat.size} and color is ${hat.color}`;
  },
};
hat.introduction();
```
// Output - `The size of hat is medium and color is green`

9. What does the following code print to the console?

```js
let hat = {
  rating: function () {
    return 'Hat is top rated';
  },
  color: 'green',
};
console.log(hat.rating());
```
// Output - 'Hat is top rated'

10. What does the following code print to the console?

```js
let bucket = {
  capacity: '5 Litre',
  customerMessage: function (desiredSize) {
    if (desiredSize > 5) {
      return 'This bucket is not large enough for you';
    }
  },
};
console.log(bucket.customerMessage(13));
```
// Output - 'This bucket is not large enough for you'

11. What does the following code print to the console?

```js
function globalFunction() {
  return 'I can be called anywhere';
}
let obj = {
  func: globalFunction,
};
console.log(obj.func());
```
// Output -  'I can be called anywhere'

12. What does the following code print to the console?

```js
let student = {
  age: 21,
  address: {
    city: 'Dharamshala',
    state: 'Himachal Pradesh',
  },
};
console.log(student.address.city);
```

// Output -  'Dharamshala'

13. What does the following code print to the console?

```js
let student = {
  age: 21,
  address: {
    city: 'Dharamshala',
    state: 'Himachal Pradesh',
  },
};
student.address.zip = '176057';
console.log(student.address.zip);
```
// Output - undefined

14. What does the following code print to the console?

```js
let student = {
  age: 21,
  address: {
    city: 'Dharamshala',
    state: 'Himachal Pradesh',
  },
};
console.log(student); // student
delete student.age; 
console.log(student); // {address: student.address}
```
// Output - 

15. What does the following code print to the console?

```js
var altcampus = {
  batch16: {
    totalStudents: '11',
  },
  batch15: {
    totalStudents: '9',
  },
  batch14: {
    totalStudents: '8',
  },
};
console.log(altcampus.batch16.totalStudents);
```
// Output - 11

16. What does the following code print to the console?

```js
var obj = {
  name: 'Panther',
};
console.log('name' in obj);
```
// Output -  true