> Let's agree on something before we start, arguments and parameters are 2 names that are pointing to the same thing, but from different directions. When we say argument, we mean the data that are passed to the function when it gets called `foo(3)`. When we say parameters, we mean the definition of the variables that the function will get `function foo(int a)`.

In dart, when you create a function with parameters, you will have to pass the arguments in order, for example:

```dart
void main() {
  positional(10, 20);
}


void positional(int num1, int num2){
  print(num1 - num2);
}
```

Here the order of passing arguments is very important. Try to change the arguments, for example, pass 20 first, then 10, you will see the order is very important here. And that's the normal behavior of functions. You have to pass the arguments by the same order you defined your parameters.

## Named argument `{ }`

Imagine you have a function that takes multiple numbers as follows:

```dart
calculateProfit(50, 2, 0.3)
```

How would you know what value should be passed first? You need some sort of labeling to identify that this is the cost, and that is the profit margin, and that is the tax, etc...
To do that with the positional arguments, we will have to memorize the order, which is a bad idea!

That's why, dart introduced namedArguments! These are parameters that can be passed in any order by passing the name of the parameter followed by the passed value. For example:

```dart
void main() {

  calculateProfit(cost: 50, tax: 2, profitMargin: 0.3);

}


void calculateProfit({required double cost, required double num2}){

  print(num1 - num2);

}
```

The main difference, when defining a function, between the positional argument function and the named argument function, is that the named argument function should have curly brackets `{ }` that surrounds all the arguments.

> Note: Here the order of passing arguments is not important. Try to change the arguments, for example, pass num2: 20 first, then num1: 10, you will see the order is not important here.

## `required` value

Note: in the above example, the **`required`** is required to add when defining a named argument function. the `required` keyword forces you as a developer to pass a value to the function.

## default value

```dart
void main() {

  namedSubtract(num1: 10);

}


void namedSubtract({required int num1,  int num2 = 20}){

  print(num1 - num2);

}
```

> Here, we set a default value for the second argument `num2`, so if the programmer didn't pass a value for this `num2` argument, the computer will take the default value.
> Here, we set a default value for the second argument `num2`, so if the programmer didn't pass a value for this `num2` argument, the computer will take the default value instead. And that's why we could remove the keyword `required`, because you ignore passing that argument, because there is a default value!
