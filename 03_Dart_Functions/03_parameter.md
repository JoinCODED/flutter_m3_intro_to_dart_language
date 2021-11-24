
create a function called convetDollarsToEuros that prints how much 1 dollar in euro

That should be easy,[ let's google how much 1 dollar in euros ](https://www.google.com/search?q=%241+to+euro)

Based on your answerr create this function

```dart
convertDollarsToEuros(){
 var euros = 0.82 * 1;
 print("1 dollar is $euros euros")

}
```



Now let's call this function in main 

```dart
void main(){
 convertDollarsToEuros()
}
```



Now, let's convert 4 dollars to euros. 

Do you think we need a new function to calculate 4 dollars in euros? 

```dart
convert4DollarsToEuros(){
var euros = 0.82 * 4;
 print("4 dollar is $euros euros")
}
```



Notice that both functions do the exact same job, with 1 value difference. Which is number of dollars. What if we could create 1 function that can take a number, and calculates based on that number. So every time, when we call `convertDollarsToEuros` we call it this way `convertDollarsToEuros(4)` to convert $4. And `convertDollarsToEuros(8)`. That's why the parentheses are useful! They are used to pass data to functions. So how do we do that? 

```dart
convert4DollarsToEuros(double dollars){
    var euros = 0.82 * dollars;
    print("$dollars is $euros euros")
}
```

Now this function can convert any amount of dollars to euros! 



## Multiple parameters

We can take more than one parameter in a function by separating each parameter with a comma





