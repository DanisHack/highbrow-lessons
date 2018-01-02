# Episode #8 of 10 - Optionals

![](https://4cawmi2va33i3w6dek1d7y1m-wpengine.netdna-ssl.com/wp-content/uploads/2017/06/8-4.jpg)

Have you ever wished you could win the lottery? I know I have. In fact, I'm not sure I know anyone who hasn't wished that!

Let's say you created a variable every time you bought a lottery ticket, and this variable (or bucket) held all your lottery winnings if you won. This seems to make sense, right? But what happens if you don't win the lottery? What is the variable supposed to hold? And more importantly, what happens if we're using that variable in other places in our code? Chances are, we won't win the lottery (unfortunately), but as developers, we need to be able to handle these situations!

## Code

Let's go back to one of our first lessons when we created a variable. We want to give it a name and declare what type of value should be in it:

```swift
var lotteryWinnings: Int?
```

When we declare the type of value that should be in it, all we're really saying is, "There will be an Integer in here at some point!" But what's with the question mark after Int?

The question mark is to denote an optional; in other words, this value may or may not exist. So, what would happen if there wasn't a value in lotteryWinnings (aka we didn't win) and we tried to use the variable in code? The console would print out nil, and we could potentially get a crash!

```swift
print(lotteryWinnings)
*The above code would print out nil because lotteryWinnings has no value yet.*
```

The built-in print() function in Swift is handy because if it is asked to print an empty value, it simply prints nil. This is not the case in some other functions or if we were trying to use an optional value in other ways. Try forcing print() to use the value of lotteryWinnings by adding an exclamation mark at the end (!) like so:

```swift
print(lotteryWinnings!)
```

What do you get?

Unexpectedly found nil while unwrapping an optional value

Yikes! The console tells us that we have a major problem! We've tried to **force unwrap** or use the value of lotteryWinnings when there's nothing there.

To fix that, go ahead and remove the exclamation mark and assign a value to lotteryWinnings.

```swift
lotteryWinnings = 50000
```

If we went ahead and ran the print function again, the console would print out "50000".

So, how would we deal with optionals in a more real-life setting? We could write some conditional code to check if we won the lottery before trying to use the value of `lotteryWinnings`. This would avoid any crashes and execute code only if it makes sense to. Consider the following example:

```swift
if lotteryWinnings != nil {
  celebrate()
}
```

Whoa, what is this weird syntax? The `!=` is basically an operator that means **not equal**, and nil is a way of saying "nothing." What the piece of code is really saying is, "If your lotteryWinnings **is not nothing**, execute this line of code. If not, just ignore this!" Now, if we win the lottery and have a value in our `lotteryWinnings` variable, we can `celebrate();` if not, the line of code will be skipped and we will avoid a crash!

## Tying It into the Big Picture

Optionals might be tricky to understand at first, but as you begin to write code, you will get the hang of how they operate and the safety net they provide. Like you saw above, optionals can be **explicitly unwrapped** with a `!`. This isn't always recommended, as it's basically stating, "I am a good programmer, and I know for a fact that there will be a value in this variable every time!" So, only explicitly unwrap variables if you know for sure there will be a value!

## Recommended book

- [iOS Programming: The Big Nerd Ranch Guide by Christian Keur, Aaron Hillegass](https://www.amazon.com/gp/product/0134390733/ref=as_li_qf_sp_asin_il_tl?ie=UTF8&tag=highbrow01-20&camp=1789&creative=9325&linkCode=as2&creativeASIN=0134390733&linkId=313bcff6dac4978397d53edb8005b8ab)
