# Lesson 1: Hello World

Head over to [https://gobyexample.com](https://gobyexample.com) and click on the first link, _"\_Hello World_"\_.  On each example page, you will see a description on the left and code examples on the right.

![](/assets/gbe-hello-world.png)

Any code block can be run right in your browser by clicking the tiny gopher in the top right of the code block. This is the easiest way to get started with Go, since we don't have to install anything on your computer!

**Click the tiny gopher in the top right.**

You are now on the [Go Playground](https://play.golang.org/) web site. The Go Playground lets you run Go code easily, right in your browser.

**Click the **`Run`** button.**

When you run the code, it gets run on the Go Playground's servers, and the output of the program is printed in the bottom section of the screen. You'll see in the bottom it says "Hello World" then in a gray font "Program exited.". The "Hello World" came from our program, and the "Program exited." is from the Go Playground letting us know that the program finished running.

**In the code, change "Hello World" to say hello to yourself!**

If your name is Alexie for example, edit the program so that the program outputs _"Hello Alexie"_. Then click `Run` and it should say hello to you. Awesome! You've just written some Go code!

Developers refer to the process you've just undergone as the "dev loop" or "development loop". It means writing some code, running it to see how it works, and deciding what to do next. You repeat this process until your code works as desired.

**Let's try something new:**

Select and copy the line of code that is printing out "Hello World" and past it a few times, and have it write out a story. You might end up with something like this:

```go
fmt.Println("Hello Alexie.")
fmt.Println("I am so glad to meet you!")
fmt.Println("Are you ready to learn some Go?")
```

There's a special character called a "newline" that starts a new line in the output of the program instead of printing a letter or number. The newline is usually written as `\n`. Try adding `\n` to your story.

For example, you could write:

```go
fmt.Println("Hello Alexie\nWelcome")
```

## Challenge

1. Rewrite your program so that you only make use of **a single print statement** while still outputting your story on **multiple lines**.
2. `fmt.Println` automatically puts a newline at the end of your string. Alter your code to make use of `fmt.Print` instead while still displaying your story on multiple lines when your program is executed.

## Optional Installs

If you're comfortable, feel free to install Go to your local computer and use an editor you'd like, but don't spend too much time on it:

* Go can be downloaded at [https://golang.org/dl/](https://golang.org/dl/)
* Our editor of choice is [Visual Studio Code](https://code.visualstudio.com/)



