
Strings are a special data type that can include texts. We're going to tackle some main points in strings. 



## String methods

when you store a string in a variable, you can get a lot of information of it, or you can apply some actions on it. For example, you can know what's the length of a string, or get an upper cased version, or lowered case version. You can access all of those features by simply writing the string name then add a dot after it. Wait a second, and you will see all features and actions available inside the string. try some of them out! 

![screenshot](https://lh6.googleusercontent.com/zNjupsHgQP0oIieYBweT7pqcb_rezDDxnNGY08faQlvdYicD-xL3yJNmkkv2sGpkn8VJw1hhLmDNpp30EKDFHO8gTZd6i7c2S0d8J68xTXRIk1Pl9S_JyiKQ8gJqK4hTiDMips-N)




Whenever you select one of them, checkout the documentation and see examples of how you sould use the command. 

![screenshot](https://lh3.googleusercontent.com/CROWfBbAVoHzdvnYG_0mGhKqOC_HFqZBaL2D1nYWdxq4LZ7A0EMxHhnkieZ0KflNLtrRf04Nhyg_t5Hy1_15Q6qEnNZq7dOb3lc2gJc9et5u7KfxnlBxAPP1J8d6YIrmt8TRSmhb)








## **Concatenation**

![screenshot](https://lh3.googleusercontent.com/Mz3V-uhONyjTHvqWPA2I2xczwcHgmxJIdtO3bVkDRn1tGiGSu1fACQUTihQ-coXS2akcSiLbhvaNB9nIRhXoX1gkF46dGZST989zlo7leoV1tLPJTOUZopRzqmO_5jL4ew8oDapM)


> The action of linking things together in a series, or the condition of being linked in such a way.
> **"the concatenation of lists"**



Try printing variables this way

```dart
String animal1 = "Cat";
String animal2 = "Frog";
print(animal1);
print(animal2);
```

To merge them together, we need to concatenat. To conatenate values, open quotation marks. Write variables inside, but before each variable add a dollar sign. 

```dart
print("$animal1 $animal2");
```



This is going to print 

```shell
Cat Frog
```



You can now add anything in between 

```dart
print("Hello, the first animal is: $animal1, and the second animal is: $animal2");
```

**Output**:

```shell
Hello, the first animal is: Cat, and the second animal is: Frog
```



This looks like a single text, but whenever you add a dollar sign inside quotation marks, it's going to look for variable name and replaces that value of it inside that text.09_arithmatics



> **Note**: If you try to concatenate a string with a dot sign to access a string method, you won't get what you're looking for. Notice how `.length` was literally printed out. 

![screenshot](https://lh4.googleusercontent.com/ZBUqu2cQcmxjf0t35PKvUwf0DdNfUn9lh0JVNEPDzCJ0LN6cMRtdQX62ishSB92Wt1Sv4N1lpYUQix7sEfwTxlxdH7WutNR0ucKE4hr0e6c3B-Hz_R_3kGCu6YHehoyTvmglmyz1)




And that's because the $ sign takes one word only. to enable to take an expresison of more than on word (with access a method), you should wrap the expression with curly brackets.

![screenshot](https://lh5.googleusercontent.com/ibCstBydt4nfkxupQiBo4atqxuqWCA6zFKtW3AENcU5wkU8X9W4Pb3k8RRckRHot5PWgdAewVXUopG24fbT2nq8wpID27uOhAlq7gdbjq4fh7OowqVv1U-ym8bPDVwgCDpO7hoDB)

























