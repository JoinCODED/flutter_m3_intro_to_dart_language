# **Understanding variables**

What's the longest word in the world? 🤔

iiiiit's, `Supercalifragilisticexpialidocious` 😲 </br></br>
![screenshot](https://lh4.googleusercontent.com/Zj8oQs6lmgT-vxua9v5QCdRb_x2m02sDJF8nLVgsmLDGnzWjNnsjFk9XifwCGpWxpCY5XqXH1OGCyzrYyLfTinY0K-tZZWmyg-5qsellyXPiwc-untQkhKE6WZ3ZTD_zfq7JgQmj)




I'm not sure if you are familiar with this word or this movie, but anyways, imagine your password is `Supercalifragilisticexpialidocious` and everytime you have to type it correctly. Wouldn't it be easier if you have a shortcut? how? so instead of writing a very complicated word everytime, let's have a short word that represents it. For example when I say `password` I mean `Supercalifragilisticexpialidocious`. That what the programming is able to do! 





In progamming we store values in the computer memory using a specific **name** for the variable. So let's do it! 

```dart
void main() {
  var password = Supercalifragilisticexpialidocious
}
```



If you try to run this code, it won't work because of 2 mistakes. 

	1. For every dart code (creating variable, printing, or any other command, we should end the line with a semicolon ` ; ` 
	1. For every text in programming, it should be represented between quotation marks `"like this"`.



Let's fix it

```dart
void main() {
  var password = "Supercalifragilisticexpialidocious";
}
```







