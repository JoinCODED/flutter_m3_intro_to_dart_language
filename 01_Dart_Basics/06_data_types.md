# Data types



In the pizza example, let's try changing the pizza value to **"No Pizza"** instead of 0. 
<img src="https://lh6.googleusercontent.com/_qOw03RaY5jKrYc-r1LpRjXH-K3bS0acIk2EQdF6rXfWK3zVQI98YF62i6BqZ5sYIElGouryCZpiNN1Uz-rlc9gjFv8p-OA0UXanf1MsPIvFo_mlI8htoXd87X_dDeN9HP3gb7vT" alt="img" width="800" />




What happened! Look at the red line under "No Pizza". It's indicating that the error is at this part of the code. Let's look at the console. 

> Error: A value of type 'String' can't be assigned to a variable of type '**int**'.What is String? What is **int**? What's going on! 😢

If you click on the word `pizza`, and looked at the documentation that dartpad.dev offers at the bottom right corner. You will see `int pizza`. And `int` is a short of `integer`, which is the type of this variable. 
<img src="https://lh4.googleusercontent.com/Hqmx5IHXYguQiJFEUiYjpLpH9r5O4lHadrMLcIiof4Fi7OgkkykvoOxhfRd9CiQZUvGAUUEzA8LAb82Z9OdIwJsNj2x7TcYQVzjF3Iv4bM4WMS9Km2Csug3BNP-FGF-tQ1l1fCzT" alt="img" width="800" />




So basically, in dart language, when you define a variable, that variable has to have 2 main things. 

 	1. Name 
 	2. Type



And once a variable is assigned to a specific type, you can't assign a value to it from another type.

For instant, our variable pizza was assigned to a value of 6. 6 is an integer. That's why it was stored in the computer as an integer. Now if you try to assign it a value that's not an integer. For example, 2.5, it's not going to be allowed!





### The 4 most common data types
<img src="https://user-images.githubusercontent.com/24327781/140642208-95bb2719-7aa6-4f8f-9dfc-c771882a1232.png" alt="img" width="800" />



### Why there are data types?

<img src="https://lh3.googleusercontent.com/YJGzlD-LMAPVQ9EhNGfekNs95O4SX4zieS3yJq0MfV_3qBbZtg8-fvojEJJCATU5RzhPP1VNIVnUPkiD9Ew09PmMWKeRzTTpgOaI72fxSJJPlASTlwnBYqOo0xYZ9wo_GBsfu2VG" alt="img" width="400" />

You know what is this right? It's a closet! 👕

Give yourself a moment to look at the image. What do you notice? 🤔

You notice that the big items are placed together like jackets. Small items are together like hats 👒. 

Okie dokie, so what does that have to do with data types?, you might ask 😆.

Each data type has a different size. For example, an integer has less details than double, since the distance between 1 to 2 for int is just a single step. But double can have 1.1, 1.2, 1.3, 1.3001, etc… That's why they have different sizes. And different sizes should be stored in different places in the computer memory. 







































