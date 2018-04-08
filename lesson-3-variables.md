# Lesson 3: Variables

1. Go back to [https://gobyexample.com](https://gobyexample.com/) and click on the second link, "[Variables](https://gobyexample.com/variables)"
2. Read through the description and the code example
3. Out of all these ways to define variables, which is your favorite, and why?
4. Open the code up on the Go Playground
5. Write the sentence from the last exercise, but this time, use a variable for each CAPITAL
6. What happens if you define a variable with the wrong type? Try it out!
7. What happens if you try to set the same variable to a different type? Try it out!

For example:

```go
f := "short"
f := 5
```

## Discuss

Why would it be useful to define a variable?

## Challenge
Variables are perfect for storing data that can be used later on within a program.

Update the challenge from Lesson 2 to use variables for your `name`, `age`, `color`, and `money`.

## Advanced Challenge
In Go, it is common to assign the results of a function to one or more variables. For this challenge update the code from above to use `fmt.Sprintf`, which will return a string version of the formatted output, and store the return value to a new variable named `msg`.

Then use `fmt.Print` to print the newly created variable.

## Additional Resources

* Slides [8-10](https://tour.golang.org/basics/8) of the Go Tour "Basics"
