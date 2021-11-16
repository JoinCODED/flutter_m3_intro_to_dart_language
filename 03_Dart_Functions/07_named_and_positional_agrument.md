# Named and Positional Argument



## Positional argument

They are same as default parameters. 

```dart
void main() {
  
  positionalSubtract(10, 20);
  
}


void positionalSubtract(int num1, int num2){
    
  print(num1 - num2);
  
}
```

> Note: here the order of passing arguments is very important. Try to change the arguments, for example, pass 20 first, then 10, you will see the order is very important here.



## Named argument

These are parameters that can be passed in any order by passing the name of the parameter followed by the passed value. For example:

```dart
void main() {
  
  namedSubtract(num1: 10 , num2: 20);
  
}


void namedSubtract({required int num1, required int num2}){
  
  print(num1 - num2);
  
}
```

> Note: here the order of passing arguments is not important. Try to change the arguments, for example, pass num2: 20 first, then num1: 10, you will see the order is not important here.



## required value

Note: in the above example, the **required** keyword, which tells the compiler, to use this function you need to pass these arguments.





## default value

```dart
void main() {
  
  namedSubtract(num1: 10);
  
}


void namedSubtract({required int num1,  int num2 = 20}){
  
  print(num1 - num2);
  
}
```

> Here, we set a default value for the second argument `num2`, so if the programmer didn't pass a value for this `num2` argument, the compiler will take the default value.



