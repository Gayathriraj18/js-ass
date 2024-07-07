# js-ass

CODE 1:
```
let age = 30;
const name = "Alice";
console.log(age,name);
```
# OUTPUT:

![image](https://github.com/Gayathriraj18/js-ass/assets/94154854/93b0dd47-0d37-453b-8c19-9b2b061efdec)


CODE 2:
```
const add = (a, b) => a + b;
let a=4;
let b=5;
console.log(a+b);
```
# OUTPUT:

![image](https://github.com/Gayathriraj18/js-ass/assets/94154854/d23e7231-2b4b-493c-97ea-72fa632a0d75)

CODE 3:
```
const name = "Alice";
const age = 30;
console.log(Hello, ${name}! Your age is ${age}.);
```
# OUTPUT:

![image](https://github.com/Gayathriraj18/js-ass/assets/94154854/a75582f7-8947-4ed0-a8a0-bb5508849e90)


CODE 4:
```
const person = { firstName: "Alice", lastName: "Johnson" };
const { firstName, lastName } = person;
console.log(firstName);
console.log(lastName);
```
# OUTPUT:

![image](https://github.com/Gayathriraj18/js-ass/assets/94154854/d08a54b1-9575-46fe-b2a2-fc6ce8383434)

CODE 5:
```
const array = [1, 2, 3, 4, 5];
const [first, second] = array;
console.log(first);
console.log(second);
```
# OUTPUT :

![image](https://github.com/Gayathriraj18/js-ass/assets/94154854/0fe2349a-46fe-49c7-8793-4c630659313c)

CODE 6:
```
const array1 = [1, 2, 3];
const array2 = [4, 5, 6];
const combinedArray = [...array1, ...array2];
console.log(combinedArray);
```
# OUTPUT:

![image](https://github.com/Gayathriraj18/js-ass/assets/94154854/0a68a776-3cac-4156-9825-45a3dd36b201)

CODE 7:
```
const sum = (...numbers) => {
return numbers.reduce((total, num) => total + num, 0);
};
console.log(sum(1, 2, 3, 4, 5));
console.log(sum(10, 20, 30));
```
# OUTPUT :

![image](https://github.com/Gayathriraj18/js-ass/assets/94154854/c13025db-ccac-43a7-a132-7e3d0441c619)

CODE 8:
```
const greet = (name, greeting = "Hello") => {
return ${greeting}, ${name}!;
};
console.log(greet("Alice"));
```
# OUTPUT:

![image](https://github.com/Gayathriraj18/js-ass/assets/94154854/580bf8f8-4d99-4f07-88d3-13c7ab886c7e)

CODE 9:
```
class Animal {
constructor(name) {
this.name = name;
}
}
class Dog extends Animal {
bark() {
return ${this.name} says: Woof!;
}
}
const myDog = new Dog("Buddy");
console.log(myDog.name);
console.log(myDog.bark());
```
# OUTPUT :

![image](https://github.com/Gayathriraj18/js-ass/assets/94154854/30564db0-ee6b-467f-a1b1-4c0f082e1675)

CODE 10:
```
function waitAndReturn() {
return new Promise((resolve) => {
setTimeout(() => {
resolve("Done");
}, 2000);
});
}
async function callWaitAndReturn() {
const result = await waitAndReturn();
console.log(result);
}
callWaitAndReturn();
```
# OUTPUT:

![image](https://github.com/Gayathriraj18/js-ass/assets/94154854/72d2b87c-a410-4132-bcbc-a52c1b344889)




