# Introduction to Kotlin Programming language

Kotlin is a modern, statically-typed programming language that has gained widespread popularity in recent years, especially in the world of Android app development. Developed by JetBrains, the creators of popular integrated development environments like IntelliJ IDEA, Kotlin was designed to be concise, expressive, and fully interoperable with Java.

One of Kotlin's standout features is its focus on enhancing developer productivity. It achieves this by eliminating boilerplate code, providing strong type inference, and offering powerful language constructs. Kotlin also brings functional programming capabilities to the table, making it suitable for a wide range of applications, from mobile app development to server-side programming and more.

In this introduction, we'll explore some key aspects of Kotlin, including its syntax, primary use cases, and how it simplifies everyday programming tasks. Whether you're a seasoned developer looking to expand your language repertoire or a beginner eager to learn a versatile and efficient language, Kotlin has a lot to offer.

# Writing first program in Kotlin

```
fun main() {
    println("Hello, World!")
}

```

Here's a breakdown of what's happening in this program:

* `fun main()`: This defines the `main` function, which is the entry point of our program. In Kotlin, `fun` is used to declare a function, and `main` is the name of the function. The empty parentheses `()` indicate that this function doesn't take any arguments.

* `{}`: These curly braces enclose the body of the `main` function, where our code goes.

* `println("Hello, World!")`: This line is inside the `main` function and uses the `println` function to print the text "Hello, World!" to the console. `println` is a built-in function in Kotlin for printing text with a newline character at the end.

# Create birthday message in Kotlin

```
fun main() {
    val friendName = "John" 
    val age = 30 

    println("Happy Birthday, $friendName!")
    println("You are $age years old today. 🎉🥳")
}

```

In this program:

* We define a `friendName` variable to store friends name.
* we define an `age` variable to store friends age.
* We use string interpolation to include the values of `friendName` and `age` in the birthday message.
* Finally we use `println` to print the birthday message to the console.

***

Notes created on 22/08/2023