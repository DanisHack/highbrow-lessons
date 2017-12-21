# Episode #4 of 10 - Functions

![](https://4cawmi2va33i3w6dek1d7y1m-wpengine.netdna-ssl.com/wp-content/uploads/2017/06/4-4.jpg)

Did you ever play "Simon Says" in school? If so, then you already have a leg up on how functions work!

Simon Says hinges on the principles of strict instructions. If you miss an instruction, you lose (or your code breaks). You are basically the leader of a Simon Says game, and the people playing are your functions. You tell them what to do, but be sure to be explicit!

## Code

Now for the fun stuff! Let's say you wanted to write a function that added $2,000 every time you got paid. Let's break down what we'll need:

- A variable (or bucket) to hold a bank account balance
- A variable (or bucket) to hold the amount of our paycheck
- A function to add our paycheck to our bank account balance

Let's first declare our variables:

```swift
var bankAccount = 0
var paycheck = 2000
```

We're broke. :( But not for long! Now let's write a function to add our paycheck into our bank account:

```swift
func addPaycheck() {
  var newBalance = paycheck + bankAccount
  bankAccount = newBalance
}
```

We created a variable inside our function that basically adds our paycheck to our current bank account. Then we assigned the new balance value to our bank account variable. You might be thinking: adding variables is a no brainer, but what is with all this syntax?

First off, you create functions by writing `func` followed by whatever name you choose for your function. Choose one that describes what the function does (i.e. `addPaycheck`). This is then followed by an open and closed parenthesis. Later down the line, you might add some things inside the parentheses, but for now, they stay closed. After that, you add an open curly bracket, and everything after this bracket will be what the function actually **does**. The function will stop running whenever the compiler reaches the closed bracket at the end.

## Tying It into the Big Picture

What's great now is that we can call this function whenever we need to add our paycheck, simply by writing:

```swift
addPaycheck()
```

For example, you might receive a paycheck every two weeks, but also one when you achieve a milestone or goal. We can execute `addPaycheck()` inside of other functions that might handle our payments, as well as the one that handles our milestones. Once you have the ability to write functions, the possibilities expand exponentially!

We can put this anywhere in our code, and it will do as we had explicitly stated, just like Simon Says!

## Recommended book

- [Swift for Beginners: Develop and Design by Boisy G. Pitre](https://www.amazon.com/gp/product/B018KYYDMS/ref=as_li_qf_sp_asin_il_tl?ie=UTF8&tag=highbrow01-20&camp=1789&creative=9325&linkCode=as2&creativeASIN=B018KYYDMS&linkId=997cba24a0885e9386067daa5bb228bf)
