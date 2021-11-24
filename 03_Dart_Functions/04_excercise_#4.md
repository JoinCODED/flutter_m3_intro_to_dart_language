
Wrtie a function called `convertKdTo` that takes 2 parameters. 

1. `value` of type double, which is the value in kd.
2. `currency` of type string, which is the currency you want to convert to. Support only 2 `usd` for dollars, `eur` for euros. Google them to know the values equivalent to kwd. 



You will call the function like this 

convertCurrrency(5, "usd") // this should print around 16 usd

convertCurrrency(5, "eur") // this should print around 13 eur

```dart
void main() {
  
  kdToCurrency(5, "usd");
  kdToCurrency(5, "eur");
  

}

void kdToCurrency(double value, String currency){
  var dollars = value * 3.33;
  var euros = value * 2.73;
  var pounds = value * 2.35;
  
  if(currency == "usd"){
    print("$value kwd is $dollars $currency");
  }
  else if (currency == "eur"){
    print("$value kwd is $euros $currency");
  }
}
```

