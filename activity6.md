# Activity

### Part 1/3

1. Create a variable for your name, another one for your age, and another one for whether you can code JavaScript or not.

Log to the console the following sentence, where name, age and true/false are variables:

```text
Hello, my name is Mirja, I am 21 years old and I can code JavaScript: true.
```

2. What are the types of the variables listed below? Verify this with typeof and output the result to the console:

```js
let val1 = 'Metropolia'; 
let val2 = "AMK"; 
let val3 = undefined;
let val4 = null;
let val5 = 500;
```

3. Create a variable that contains a value in miles e.g 54, convert it to kilometers, and log the value in kilometers in the following format:

The distance of 84 miles is equal to 135.18456 km

- Note: 1 mile equals 1.60934 kilometers.

### Part 2/3


**Numbers**

1. Enter the following expressions into your console.

   ```js
   1 + 2
   3 * 5
   5 / 4 - 13
   5000 * 234
   1073 / 57 + 200
   ```

2. Why are the values produced by the following two expressions different? What
   are they?

   ```js
   3 + 2 * 4 - 1
   (3 + 2) * (4 - 1)
   ```

3. Calculate 50 years in minutes using the console.

4. What is the percentage of letters in the Finnish alphabet that are vowels? Use the console to find out.

5. Try the following expressions in the console:

   ```js
   6 % 2
   42 % 10
   5 % 2
   6 % 3
   7 % 4
   100 % 12
   ```

   What is the significance of the result? How does the `%` (modulus) operator
   work?

6. Try the following:

   ```js
   3 % 2
   4 % 2
   5 % 2
   6 % 2
   ```

   What do the results tell you about the first operand to the modulus operator?

**Strings**

1. Write a string that represents your full name.

2. Write a string that represents your favorite food.

3. Use the `+` operator to combine (known as *concatenation*) two or more
   strings, *e.g.*:

   ```js
   // Your first and last names
   "John" + " " + "Doe"
   ```

   + Your first and last names (as shown above)
   + Your best friend's full name
   + Your home town, state and country


4. Fix the errors in the following strings:

   ```js
   Where are all the quotes?
   'hmm something is not right"
   'Do other ' * 'operators work with string concatenation?
   ```

### Part 3/3: Functions

**Basic Requirements**

1. In your console, copy the following function and verify
   that the following invocations match your expectations:

   ```js
   function square(num){
      return num * num;
   }

   square(10) + 2;
   square(100) + square(77);
   square(8 / 2)
   square(2 + 17);
   square(square(15));
   ```

2. Write a sentence in plain English describing how `square(square(15))` is
   evaluated.

3. Rename `square`'s `num` parameter in your above code to `monkey`, and
   rename the uses of that parameter in the body to `monkey` as well. Will the
   function `square` still work? Why or why not?

4. What is wrong with the following definitions of `square`? Write a sentence or   two describing the issue(s); then, try copying the erroneous examples into a   console one-at-a-time and observing the error(s) generated (you may have to   attempt to invoke the functions to see the error). What errors are produced   (if any) for each erroneous version? Do the errors make sense?

   ```js
   function square(banana) {
     return x * x;
   }

   function square(5) {
     return 5 * 5;
   }

   function square("x") {
     return "x" * "x";
   }
   ```

5. Fix the invalid syntax in the following functions (you can copy and paste these
   invalid definitions into your console and then edit them there):

   ```js
   func square1(x {
     return x * x;
   }

   functionsquare2 x)
     return x * x;
   }

   function (x) square3 {
     return x * x;
   ```

6. The following functions exhibit poor style -- fix these issues using the
   original version of `square` as a reference.

   ```js
   function square(x){return x*x;}

   function square (x) { return x *x;
   }

   function square(x)
   {
   return x * x;
   }
   ```

7. Complete the function `cube` that returns the cube of x:

  ```js
  function cube(x) {
    // your code here
  }
  ```

8. Complete the function `fullName` that should take two parameters, `firstName`
   and `lastName`, and returns the `firstName` and `lastName` concatenated
   together with a space in between.

  ```js
  // don't forget the parameters!
  function fullName() {
    // your code here
  }
  fullName("John", "Doe") // => "John Doe"
  ```

9. Write a function `average` that takes two numbers as input (parameters), and
   returns the average of those numbers.

10. Write a function `greeter` that takes a name as an argument and *greets*
    that name by returning something along the lines of `"Hello, <name>!"`
  

### Reference
- [Hack Reactor](https://github.com/hackreactor/javascript_101)