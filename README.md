# js_program

# Exercise 1: Let and Const
```
let age=30;
const name="Alice";
 name="bob";
 console.log(name)
 ```

 output:
 ![alt text](<Screenshot 2024-07-06 081845.png>)


# Exercise 2: Arrow Functions
```
const add=(a,b)=>{
    console.log(a+b) ;
}
add(4,6);
```
output:
![alt text](<Screenshot 2024-07-06 082005.png>)

# Exercise 3: Template Literals
```
let name="Alice";
let age=30;
let txt=`Hello,${name} Your age is ${age}.`;
console.log(txt);
```
output:
![alt text](<Screenshot 2024-07-06 082120.png>)

# Exercise 4: Destructuring Objects
```
const person={
    firstName: "Alice", 
    lastName: "Johnson"
}
const{firstName,lastName}=person;
console.log(firstName);
console.log(lastName)
```
output:
![alt text](<Screenshot 2024-07-06 082218.png>)

# Exercise 5: Destructuring Arrays
```
const numbers = [1, 2, 3, 4, 5];

const [first, second] = numbers;

console.log(first);  
console.log(second);
```
output:
![alt text](<Screenshot 2024-07-06 082300.png>)

# Exercise 6: Spread Operator
```
const arr1 = [1, 2, 3];
const arr2 = [4, 5, 6];

const combined = [...arr1, ...arr2];

console.log(combined);
```
output:
![alt text](<Screenshot 2024-07-06 082414.png>)

# Exercise 7: Rest Parameters
```
const sum = (...numbers) => numbers.reduce((acc, current) => acc + current, 0);

console.log(sum(1, 2, 3, 4, 5)); 
console.log(sum(10, 20));        
console.log(sum());
```
output:
![alt text](<Screenshot 2024-07-06 082453.png>)

# Exercise 8: Default Parameters
```
const greet = (name, greeting = "Hello") => `${greeting}, ${name}!`;

console.log(greet("Alice"));          
console.log(greet("Bob", "Hi"));      
console.log(greet("Charlie", "Hey"));
```
output:
![alt text](<Screenshot 2024-07-06 082548.png>)

# Exercise 9: Classes and Inheritance
```
class Animal {
    constructor(name) {
      this.name = name;
    }
  }
  
  class Dog extends Animal {
    bark() {
      return `Woof! My name is ${this.name}`;
    }
  }
  
  const myDog = new Dog('Buddy');
  console.log(myDog.bark());
```
output:
![alt text](<Screenshot 2024-07-06 082654.png>)

# Exercise 10: Promises and Async/Await
```
const waitAndReturn = () => 
    new Promise(resolve => setTimeout(() => resolve("Done"), 2000));
  
  async function run() {
    const result = await waitAndReturn();
    console.log(result); 
  }
  
  run();
  ```
  output:
  ![alt text](<Screenshot 2024-07-06 082757.png>)


