# **return type functions**

So far, our functions are isolated. You call a function from main, and it prints something. There is nothing main is getting out of the function. For example, I need when I call the currency converter function, to give me something back like this. 

```dart
void main(){

     var usd = kdToCurrency(5, "usd");
}
```



Note that in this example, we're taking a value from kdToCurrency method. What we want this value to be is the converted amount right? But now our function doesn't support that. Because it doesn't return value. So how can we make it return a new value? 



First of all, think value type are you retuning? the currency is double. Then the return type we need from our function is double. Then change `void` to `double`. 

![img](https://lh3.googleusercontent.com/G4mmzrDLyA2otBMWHehS84Obw26yAIzZdT8EI67rSPfF4x6jyK5E8gNccpoduVqt38_6dUFdNzBMhnzPZUf2NMH7wlwDuKH63FThZOG5kqjfnSxCb-9Oxa1Szg7hSouZZDtj5498)



Once we replaced void with double, that means that the function is a **return type function**. a return type function should always return something using the keyword return. So now instead of printing inside the function, we will replace the printing statements into return. So we return the value instead and give it to whoever calls this function. 

![img](https://lh4.googleusercontent.com/rC0YZA2ImN86FOi5RTaqRhTE_JRmZvBB2Yavlinmv1atyW8gZQi5YgZMPiWhjN7Q2JOmNaXpW5bWUgdnLHQt-S0oUcQIvS51PV-UCZl2WDY9eI5TCw4a9t9cwx6FqvCRJPnEHvZ9)



There is still a problem, didn't we return and problem solved?

No. There is actually a case where you might send a currency that's unavailable, for example, SAR. And here comes a RULE OF THUMB. 



### **Rule of thumb**

> A return type function should return in all cases

That means that we should provide a default value to return. use `else`. 

```dart
double kdToCurrency(double value, String currency){
  var dollars = value * 3.33;
  var euros = value * 2.73;
  var pounds = value * 2.35;
  
  if(currency == "usd"){
    return dollars;
  }
  else if (currency == "eur"){
    return euros; 
  }
  else{
    return 0;
  }
}
```



Violaa! 🎉 no errors! 

Now, how to use it? 

![img](https://lh4.googleusercontent.com/piaDbTN9hcBkcbbGlGSLYDxjAM_BZpWwly1zTwqXp5R8bg__zN1DznX5-Sk3_7obPZzkQEncpCIobIMXQIFADkZSHA923DKJSFg9M63VE8NbePKVMAfz9glfg97YJ1RqbfPkw1Jf)

Always remember, a return type function gives a value after it gets excited. This value is determined by the return statement. if the function returns double, then the after the running the function, the main will get double as a value, and it can store it in a variable.

```dart
void main() {
  double usd = kdToCurrency(5, "usd");
  double eur = kdToCurrency(5, "eur");
  
  print("$usd, $eur");
}
```

`usd` now is a double variable, it's assigned to a value that's returned from kdToCurrency. 



### Understanding return

This is a juice machine, it's exactly like the functions! It take an input of type fruit, and the output is of type juice, and that exactly like the parameters.Manifacturing the juice machine, is like creating the function. When the machine is created, that doesn't mean the juice is there. We can make juice by turning on the machine, and that's equivalent to calling a function. You can make orange juice, by pressing on "ON" button on the machine, but that doesn't have to mean that you will get orange juice. If you don't place a cup under that machine, the orange juice is going be made, but spilled. That's exactly like calling a function that returns without taking it's value. like this.

```dart
kdToCurrency()
```































