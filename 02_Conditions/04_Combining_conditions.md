
What if I need to compare a value if it's between 2 values. 



### Example

You get a "B" grade if you are between 80 and 90. In other words, if you are greater than or equal to 80, **AND**, less than 90, right? So how to do that? 



#### **COMMON MISTAKE!**

```dart
var x = 86;
if(90  > x >= 80){
	// statement here
}
```

This is a horrible mistake! 

The operations `>, <, >=, <=, ==, !=` can only work for 2 sides. Left side, and right side. If you want to have a complex condition, you can use combine conditions using the logical operators which are the following.

