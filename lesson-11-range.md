# Lesson 11: Range

1. Open the "[Range](https://gobyexample.com/range)" example and read through it.

## Challenge

Modify your program from lesson 10 to use a range to iterate the map to output the following:

```
1 is odd 
2 is even 
3 is odd 
4 is even 
5 is odd 
6 is even 
7 is odd 
8 is even 
9 is odd 
10 is even
```

**HINT**: use a `for` loop with `range` to get the key and value of each entry in the `map`, then use an **If/Else** on the value.

## Discuss

When is range useful in a loop instead of the initial/condition/after classic loop style?

## Advanced Challenge

When iterating over maps the order of keys is not garunteed so running the same program multiple times will result in different outputs, as you may have noticed from the challenged above. In ordered to print a map in order the keys must be sorted separately and then used to access the fields of the key. 

Update the program above so that the map is always printed in order strating at 1, all they way to ten. 

**HINT**: use the [sort.Ints](https://godoc.org/sort#Ints) function in the [sort](https://godoc.org/sort) package

## Additional Resources

* [Interation order](https://blog.golang.org/go-maps-in-action#TOC_7.) for maps
* [Range clauses](https://github.com/golang/go/wiki/Range) on the Go Wiki



