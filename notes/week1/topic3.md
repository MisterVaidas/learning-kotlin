# Conditional behaviour in Kotlin

The primary conditional constructs in Kotlin are `if`, `else if`, `else`, and the `when` expressions.

1. `if` Statement:

The `if` statement allows you to execute a block of code if a certain condition is true. It can be used by itself or with an optional `else` clause.

```
val age = 18
if (age >= 18) {
    println("You are an adult.")
} else {
    println("You are not yet an adult.")
}

```

2. `if` - `else if` - `else` Statement:

You can use multiple `else if` clauses to handle different conditions.

```
val score = 85
if (score >= 90) {
    println("Excellent!")
} else if (score >= 80) {
    println("Good job!")
} else if (score >= 70) {
    println("Keep it up!")
} else {
    println("You can improve.")
}

```

3. `when` Expression:

The `when` expression is similar to a switch statement in other languages. It allows you to compare a value against multiple cases and execute the corresponding block of code. It's particularly useful when dealing with more complex conditions.

```
val day = 2
when (day) {
    1 -> println("Sunday")
    2 -> println("Monday")
    3 -> println("Tuesday")
    4 -> println("Wednesday")
    5 -> println("Thursday")
    6 -> println("Friday")
    7 -> println("Saturday")
    else -> println("Invalid day")
}

```

4. `when` Expression with Conditions:

You can also use conditions in `when` expressions to handle ranges, multiple values, or even execute arbitrary code.

```
val grade = 85
when {
    grade >= 90 -> println("A")
    grade >= 80 -> println("B")
    grade >= 70 -> println("C")
    grade >= 60 -> println("D")
    else -> println("F")
}

```

These conditional constructs provide flexibility in controlling the behavior of your code based on different conditions. They are fundamental to writing dynamic and interactive programs in Kotlin. Experiment with these constructs in your Kotlin environment to gain a better understanding of how they work.