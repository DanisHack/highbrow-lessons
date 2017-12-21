# Episode #5 of 10 - Bools & Conditional Logic

![](https://4cawmi2va33i3w6dek1d7y1m-wpengine.netdna-ssl.com/wp-content/uploads/2017/06/5-4.jpg)

Like many 10-year-olds, I had chores at home, like doing the dishes, folding the laundry, and taking out the trash. I tried to maintain these chores to stay in good graces with my parents so when I wanted to go out with my friends, they'd see all my chores done and off I would go!

Conversely, if I didn't do my chores, punishment ensued. I wouldn't be able to go out, and I would be grounded! It became very clear in my head that each action had a direct reaction. This is exactly what conditional logic is. Conditional logic in code basically helps us navigate the possible outcomes we have written. If a user clicks a button, what happens? If a user has already added someone to their profile, do you alter the button and UI to reflect that? Conditional logic can come in many forms of size and complexity but are crucial building blocks to software development.

## Code

Consider the above scenario in this format:

> If I do my chores, I get to go out.

> If I don't, then I'm grounded.

This is an example of an `if` statement, which is used to identify a condition and perform logic based upon those parameters. In Swift, you might write this as such:

```swift
if completeChores == true {
  goOutAndHaveFun()
} else {
  beGrounded()
}
```

There are a couple of things going on here. First, we're using a **boolean** value. A boolean is basically a data type that states if something is **true** or **false**. In this specific situation, we are asking to check if our `completeChores` object is true, and if so, then to execute whatever code precedes the bracket. The `else` piece of it is to denote what happens if `completeChores` is **not** true. In this case, I would `beGrounded`.

## Tying It into the Big Picture

Conditional logic and booleans come into play in so many areas of code. A real-world example of this could be an app you have created using a freemium model. If you have paying users and free users, they are obviously going to have access to different functionalities in the app. A piece of code to handle this could be something along the lines of:

```swift
if freeUser == true {
  limitedAccess()
} else {
  allAccess()
}
```

It may be difficult to see the entire value of conditional logic and booleans just by reading their definitions, but after you begin building out projects and continue learning, you will see just how important these are to the building blocks of programming.

## Recommended book

- [iOS 10 Programming Fundamentals with Swift: Swift, Xcode, and Cocoa Basics by Matt Neuburg](https://www.amazon.com/gp/product/1491970073/ref=as_li_qf_sp_asin_il_tl?ie=UTF8&tag=highbrow01-20&camp=1789&creative=9325&linkCode=as2&creativeASIN=1491970073&linkId=dd226c6b066c30a7fa496c9d4269516c)
