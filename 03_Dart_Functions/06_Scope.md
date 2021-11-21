# Scope



### **Think of this question**

We have 2 functions, `function1` and `function2`. `function1` defines x to have the value of 10. `function2` defines x to have the value of 100. 

In main function, we're printing x. Which value is going to be printed. 

```dart
void function1(){
  var x = 10;
}

void function2(){
  var x = 100;
}
void main() {
  print(x);
}
```

The answer is: none of them. It's a syntax error. x wasn't defined in main. 

![screenshot](https://lh4.googleusercontent.com/YUmI-Zc6hvEKXddAuII3Ww4PB22wj-TbOP1nt0UxjP3hJsFLTzrtb_n3xd0YSbVre27CE1r9guhKB4hqdXgxIfRpSt6u5vlkZxxDBg8zupJjDTsimdJbfXgezM6vYwZsUtxfa6tR)




Each function starts with an opening curly bracket and ends with a closing curly bracket. The area of code between two brackets is called a **scope**. Anything defined in a scope, is not accessible outside the scope. That's why we were able to define x in `function1` and x in `function2`, because they don't see each other. Scopes are not only for functions. Scopes are any coding area between 2 curly brackets. 



































