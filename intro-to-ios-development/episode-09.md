# Episode #9 of 10 - Functions with Parameters

![](https://4cawmi2va33i3w6dek1d7y1m-wpengine.netdna-ssl.com/wp-content/uploads/2017/06/9-4.jpg)

You're watching a football game and the coach is drawing out plays. He's showing what the quarterback will be doing, and where and when the receiver will catch the ball and score. When the ball snaps, you watch it all flawlessly unfold before your eyes. The quarterback launches a killer pass straight to the receiver, who sprints to the end zone and scores!

Believe it or not, this is very similar to how functions with parameters work. The plays carried out by those players are not exclusive but can be used by anyone! The idea of a play or plan in sports is also not entirely specific to the sport itself. For example, plays are drawn up in basketball, football, baseball, and most other sports. What's important to understand is that these are formulas that athletes practice and can be applied to anyone playing the sport.

## Code

If you recall our lesson on functions, we wrote them without any parameters, like such:

```swift
func coolFunction() {
  // Do stuff here
}
```

We can actually put elements within the parenthesis that we can use within our functions! All we need to do is give them a name, followed by their respective data type, like the example shown below:

```swift
func calculateArea(width: Int, height: Int) {
  print(width * height)
}
```

It might seem a little hard to follow, so let's use it in the context of our introduction example with a little pseudo-code:

```swift
func throwTouchdown(player1: Quarterback, player2: Receiver) {
  player1 throws
  player2 catches
}
```

Obviously, "player1 throws" and "player2 catches" are not true to syntax, but it illustrates the idea of having parameters for your functions. You'll also notice they both have their respective types. This means that since "player1" is of type `Quarterback` and "player2" is of type `Receiver`, the code should run. Now when we call this function, it will ask for these parameters, and we can put any player who fits, like such:

```swift
throwTouchdown(player1: Tom Brady, player2: Julian Edelman)
```

This pseudo-code would now run with those specific parameters (and hopefully score a touchdown)!

## Tying It into the Big Picture

As you can probably tell, functions offer a lot of flexibility to create reusable instructions within your app. A real-world example of this might be filtering through your friends list on Facebook. Most likely, there is a function that takes what you have typed in and runs it through your entire friends list, finds friends with the matching criteria, and displays it on the screen. It probably involves functions within functions!

## Recommended book

- [iOS 10 in Swift 3 by Mark Price, Caleb Stultz, Jack Davis, Evan Leong](https://www.amazon.com/gp/product/0692838740/ref=as_li_qf_sp_asin_il_tl?ie=UTF8&tag=highbrow01-20&camp=1789&creative=9325&linkCode=as2&creativeASIN=0692838740&linkId=3676ec44c6fcef3e5c6e42c1004efe0c)
