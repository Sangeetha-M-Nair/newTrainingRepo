**To make a copy of object in javascript, it provides two ways ...**

    Using Object.assign

It has 3 parts 1-target obj which is represented by {},
2-source object
3-changes we need to be added to the object

    Using spread operator represented as ...

more simpler way
eg:- let obj3 = {
...obj1,
city: "London",
name: "Sangeetha M Nair"
}

**Currying** also known as **Wrapper functions**
Currying is an advanced technique of working with functions. It’s used not only in JavaScript, but in other languages as well.

Currying is a transformation of functions that translates a function from callable as f(a, b, c) into callable as f(a)(b)(c).

It takes another function as an argument.

in js we can pass function as an argument we can also return function as a result
