```dart
void main() {
  var x = 14;
  var y = 3.1;
  var z = "Hussain";
  var i = "11th grade";
  var j = false;
}
```

This program stores some information about a student

- His age is represented by x, which is 14
- His gpa is represented by y, which is 3.1
- His name is represented by z, which is "Hussain"
- His grade level is represented by by i, which is "11th grade"
- His senior status is represented by j, which is false. He's not a senior student.

This is programmatically correct, but it's really hard to understand by developers. We need to have better names for the variables. Let's rename them

```dart
void main() {
  var studentAge = 14;
  var studentGrade = 3.1;
  var studentName = "Hussain";
  var studentGradeLevel = "11th grade";
  var isSenior = false;
}
```

### **Variable naming rules**

1. Spaces are not allowed in any name in programming.

   **Example**:

   ```dart
   var number of pizza slices = 4;
   ```

   is a syntax error. You're allowed to name your variable with a single word. If you have multiple words to represent the variable, then create the variable names by deleting spaces that separate the words. Capitalize the first letter of each word (excluding the first word), and use no separators.

   **Good examples**:

```dart
var numberOfPizzaSlices = 4;
var studentGradeInSemester2;
```

This convention is called **camelCase**.

![screenshot](https://lh5.googleusercontent.com/1A_BKQ0T2n4F6-nZ2RIOzzL7CGCFwY6tShelx1nHX6BxxeiSt5iETMgP1baVxb5NeA69HvEOcH4_BS8dnzE9oEkxbyo7BgRzWUV48Y2UPVptAuhhn_bwuZ7q--Dz3Z_YC3xhSAFI)

You keep the first letter of the first word small, and capitalize the first letter of every second word.

2. You can't start your variable name with a number.

   **Bad example**:

   ```dart
   var 2StudentsGrade;
   ```

   is a syntax error! You can add numbers in the middle or at the end of the name.

3. All symbols are not allowed `!@#$%^&\*()-“"<>{}/?~+` except for 1 symbol ` _ `

![screenshot](https://lh4.googleusercontent.com/Uo6ChSBFusHlj89S_EbzhU1dcMQiD2feohEXVtyEbijaddVkPgO4QieKPHmPZDUvgPK5eQjulAxX71Wj2NkyIDaHUy5t7U6NRcLCLvmUtQsyhAY0pgc8lO_8O34P5TBAIbf1jRO1)

**Example**:

```dart
var number_of_pizza_slices;
```

Although it's not recommended in dart language to name variables this way. But you might see it in different places. We always recommend naming variables using the camelCase convention.

4. **Good practice:** Name your variables based on the terms of the subject area, so that the variable name clearly describes its purpose. Even if it has a lot of letters for example `numberOfAvailablePizzaSlices`. It's fine to have long variable names as long as they clearly represent what this variable stands for (without exaggerating)

5. Do not use variable names that consist of a single character. Short variable names are only allowed for loop counters.
