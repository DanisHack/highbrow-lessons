# Episode #2 of 10 - Strings

![](https://4cawmi2va33i3w6dek1d7y1m-wpengine.netdna-ssl.com/wp-content/uploads/2017/06/2-4.jpg)

What is the difference between these two sentences?

- He told me I couldn't do it.
- He told me, "I couldn't do it."

Yup, you guessed it! Quotation marks! They make the difference between stating a fact and showing that someone literally stated *something*.

## Code

Interestingly, this is kind of how it works in the Swift world too. Strings in Swift (as well as most other programming languages) denote literal text through quotation marks. So, what does that mean exactly?

Consider the following example:

```swift
var age = 36
var age = "36"
```

Similar to the example in the story, these actually mean two different things. The first example (`var age = 36`) is actually declaring the variable age as a number (`36`). The second example, however, is declaring the variable age as literal text. So, how is this practically applied?

If you were creating a program that added 10 years to everyone's age, you would want to take a variable you created, named age, and add 10 (i.e. `age + 10`). This would work with the first variable we created, but not the second. Why? Since there would be quotation marks around it, it would read it as a word, not as a number. It'd be like trying to add "dog" or "nachos" to 10. It wouldn't make any sense!

## Tying It into the Big Picture

Why is this important? As you learned in the previous lesson, it matters how you label the buckets of data that you're putting information into. Strings are generally used for items like showing text on screens, and numbers are broken down into different formats that can be used in a variety of ways. Just to give you an idea, if we were to write a function that added 10 years to your age, and then displayed it on the screen, it would look something like this:

```swift
var age = 20
var newAge = age + 10
labelOnTheScreen.text = "\(newAge)"
```

Okay, whoa, what is all this? Don't worry, we'll break it down!

`var age = 20` → We are declaring that the variable age has a numerical value of 20.

`var newAge = age + 10` → We are creating a new variable called newAge and saying that its value is `age + 10`.

`labelOnTheScreen.text = "\(newAge)"` → We are basically telling the label on the screen to be the variable `newAge`. The syntax around it is called string interpolation, which is just a fancy way of saying, "convert this into a string so I can show it on the screen."

It's important to note that all these names (`age`, `newAge`, and `labelOnTheScreen`) are names that I made up. As a developer, you can name things whatever you want! There are a few rules, but for the most part, it's up to you how you want to name your variables.

I know it sounds like a lot, but feel free to re-read if it didn't quite make sense the first time around. As we continue through our journey, things will start to fall into place!

## Recommended book

- [The Joy of Swift: How to Program iOS Applications Using Apple Swift Even If You've Never Programmed Before by Alan Forbes](https://www.amazon.com/gp/product/B018ZKTYIK/ref=as_li_qf_sp_asin_il_tl?ie=UTF8&tag=highbrow01-20&camp=1789&creative=9325&linkCode=as2&creativeASIN=B018ZKTYIK&linkId=a1076e36572f7e27034e753d1eb3a0a9)
