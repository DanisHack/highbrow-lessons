# Episode #7 of 10 - Loops

![](https://4cawmi2va33i3w6dek1d7y1m-wpengine.netdna-ssl.com/wp-content/uploads/2017/06/7-4.jpg)

When I was in high school, I used to work at a restaurant (like many kids my age). Getting free food and being able to fill up your tank sounded like a dream job at 17! (Free food still sounds like a dream . . .)

As anyone who has worked in a restaurant knows, the key to staying on top of things is creating a process. Having a process for serving large parties, a process for the kitchen, a process for bussing, etc. is necessary to keeping things even-keeled.

Creating these processes is similar to something called a loop in Swift. When an order comes in to make a hamburger, the cook knows exactly what to do because he follows a created process:

- Cook the meat.
- Toast the bread.
- Add vegetables.
- Add cheese.

## Code

There are many ways you can write loops in Swift. We'll touch on one example today, which is called a **for loop**. Given the above example, a for loop to make 10 burgers in Swift could look something like this:

```swift
for burger in 1...10 {
  makeBurger()
}
```

Luckily, this syntax comes pretty close to the actual description of what we're trying to accomplish. We're basically saying that for each burger in a series of 10 burgers (or orders of burgers), perform the following function: `makeBurger()`. The syntax `1...10` basically means to start at 1 and keep performing the same action until you reach 10.

We could have picked any number as well. If we had said `1...300`, the action would have been performed 300 times. If we had said `0...<10`, the loop would run until it reached 9 because we explicitly told the loop to run while it was less than 10.

It's also important to note that we actually called a function `makeBurger()`. This function could consist of our list of things to do in order to make the burger, and we could therefore place the function anywhere in our code (including the loop we just made!). This is incredibly powerful because if we wanted to add pickles to the equation, we could go back and update our `makeBurger()` function accordingly and only have to update it once!

## Tying It into the Big Picture

Loops are incredibly powerful and are used in a variety of ways. There are also several different kinds of loops that are best used for different situations. Even though for loops are pretty popular, there are also:

- **While loops** that perform until a set condition becomes false
- **Repeat loops** that repeat so long that a certain condition is met

These will all come into play and be incredibly useful for specific situations throughout your coding career. Chances are, many of your day-to-day tasks involve loops in some way, shape, or form, so it's really a matter of applying concept to syntax and placing it where it should go!

## Recommended book

- [Swift Programming: The Big Nerd Ranch Guide by Matthew Mathias and John Gallagher](https://www.amazon.com/gp/product/013461061X/ref=as_li_qf_sp_asin_il_tl?ie=UTF8&tag=highbrow01-20&camp=1789&creative=9325&linkCode=as2&creativeASIN=013461061X&linkId=89d601e0c4b3d1c64113e93e6adf383e)
