# **Arithmatics** 

You all know math. Let's get this done quickly by looking at the following example that clears out what kind of mathematical operations you can perform in dart language. 

![screenshot](https://lh4.googleusercontent.com/GHvSnU8qeGThz8lAtBfqurJ6I8Hc1dbzfL3f4nVVsSuglhAwcs2BFIc-MjdrFmqfAHMHwnxHdOX5R1v4teiwwtpjG2165H_YVnqYeG2gKkJ5HcFF6CZ1Qy9gWsBXrj5IwyYP1dBA)




The only new operation here is [remainder %](https://en.wikipedia.org/wiki/Remainder#:~:text=In mathematics%2C the remainder is,integer quotient (integer division).). We're not going to focus on it for this module. But you can always google it. 





You can combine operations together 

![screenshot](https://lh6.googleusercontent.com/J7Vxt3ogiS6yQHiUNMtAN0y0aQqOxTME192T4Pxc7WN1__RtchDXzMiaqhi0pHw1HMQmGEFYO3xmztA9EA_mEYjTeLUjJrU68gs18raPI7eIFl9vgAJSgVa5t7MwD8_5Mdjh6OPr)




This result is wrong. Because x + y should calculated first, then we divide that by 2. We can use the priority parentheses. such like `(x + y) / 2`

![img](https://lh3.googleusercontent.com/iGw-pKXQrlStsK-faiuD9xrV6vUHwUYLtg_QgovV6HlXjQXgAMjDuZRiu4Ltccj9vt9noZtazXvGIKHnKN6JlIzkWQnb0TO0vqy7e5xI6OYcoW5q3fcy3XMNzckvJaaWGsfbI9cf)





## **Incrementing**

There is an important operation, which is incrementing. Try to think about it before you check the code. 

![screenshot](https://lh5.googleusercontent.com/nn2Rrbp2jg7tWNERXYuaQKvm51xH64JEdJJz0_fkC7D_mOTk432-Sc0BOEdm1Vw5zwKailX3khceFyxg56LuO_s2rf4Kiuv3vLvaN__63Q3zTOqGCcLVb-Snm9bCI6x7lecOdZe4)




If that what you thought about, then this is cheating! I don't say you cheated and sneaked at the answer 😜, but it's cheating on the computer. This is not incrementing! You're looking at the previious value, and incrementing it in your head, and giving the variable the new incremented value. Which is cheating. We want the computer to do the incrementing part.



So how do we increment? 

Basically, we add 1 to the previous value, and we assign the variable that value. as follows

![screenshot](https://lh3.googleusercontent.com/4jIfAMsp27OU1d7qSPPhnV11zk0pKDNUdYNJpOUT9zd4JXgzMylNrdaIaU7Y31-4bNO4f2BsQoeyNlls5ADw2xRptTffASIYzVhNC9B5i-0DGZCRgm9S5mEv9qOIgi_mZkQQ80Ku)



So basically, this is a single command, that you can use everywhere. 

```dart
counter = counter + 1;
```



If a mathematicians see this, they will freak out! 

How could a variable equals to itself + 1? 

That's because in programming the `=` sign is not equal, it's assign a new value. So `counter + 1` is going to be calculated first, then the result is going to be assigned to counter again. So counter will get the new value of counter + 1. 

**![screenshot](https://lh5.googleusercontent.com/x9CAtxDmcbRsBruOX4l1p_uWqL86CBSEDpd-JC2g4OK0rBVX--9fIp196ZjBrMzrDQlOi1xNAyIgUgKVtWWaTiJuHfQe0-Q5MxSPamUtZy0dHqh8-jf_l73D-ybftAJPuJ83AhDV)**





### Shortcut? 

`counter = counter + 1` is actually long, there is short for it. For any value that's going to incremented, you can use the expression `counter += 1`.You can also use `-=` to decrement, `*=` and `/=` to do the similar thing





