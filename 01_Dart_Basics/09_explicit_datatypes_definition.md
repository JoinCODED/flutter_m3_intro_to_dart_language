# **Explicit datatypes definition**

In the previous example,

```dart
void main() {
  var studentAge = 14;
  var studentGrade = 3.1;
  var studentName = "Hussain";
  var studentGradeLevel = "11th grade";
  var isSenior = false;
}
```

We defined all variables using the keyword `var`. But if you click on each one, and check the documentation window, you will see that they have different types. Actually, it's a good practice to define the variables explicitly by their types. Because actually `var` keyword is a magical keyword that can understand the type of a value, and recreate the variable using the explicit type. `var` is just so fancy. 



```dart
void main() {
  int studentAge = 14;
  double studentGrade = 3.1;
  String studentName = "Hussain";
  String studentGradeLevel = "11th grade";
  bool isSenior = false;
}
```

In this way, we defined our variables explicitly. There is no difference between this code and the previous one. It's just clearer for us as programmers to know what type is that variable quickly. 



> Note that all types are lower cased, except for `String`. It's start with a capital letter for some reason. Google it if you want to know.
> <img src="https://lh4.googleusercontent.com/XIqDN7nNtppvQogpbebwVqhIvRBM4Pt1xPunMD8-ZVOYBdia4MnEez0mqG6yVNSr57M835yy42r3MZ5w58vUhcd8YRWpvzhewm-YzmsteeXJbtd5ni8VpvCeETVgZMyVNxbhLqSQ" alt="img" width="300" />




