# Episode #3 of 10 - Numbers

![](https://4cawmi2va33i3w6dek1d7y1m-wpengine.netdna-ssl.com/wp-content/uploads/2017/06/3-4.jpg)

Remember when you were a kid, every year, you had to buy all new supplies for school? You had colored pencils, crayons, markers, and maybe even pastels? When the teacher gave you a coloring assignment, your seven-year-old self busted those bad boys out and started to create a masterpiece.

If you think about it, though, you rarely used each kind of coloring tool in the same piece of artwork. If you chose to color in crayon, you stuck with crayons! Mixing markers with pastels also proved to be a weird mix. Although using them together seemed off, individually, they still served their purpose: adding color where it needed to go.

# Code

Like your collection of coloring artillery, there are three main types of numbers in Swift:

- Integer
- Float
- Double

An **integer**, as you might have guessed, is a whole number. These can range from negative to positive, such as 48 or -483.

A **float** is a low-precision decimal number that can include up to six digits after the decimal point. An example of a float is 3.14, .03, or 583.38.

A **double** is a higher precision decimal that can include up to 15 digits after the decimal point and is typically used over floats due to its accuracy. An example of a double could be 4.7437428009.

## Tying It into the Big Picture

So, why do we care about the types of numbers we use? Each one is best suited for specific situations. For example, you would probably want to use a double for location coordinates, due to its precision accuracy, and maybe use an integer if you were calculating how many likes or upvotes a post had in your app.

In Swift, you can explicitly declare what type of variable you're creating. For example:

```swift
var myNumber: Int = 43
```

Here, we explicitly declare that our variable `myNumber` is of type Integer with `: Int`. What's great about Swift is that you can also just type the following:

```swift
var myNumber = 43
```

Swift automatically infers that it is of type Integer because it doesn't have any decimals! Pretty cool, huh?

Also, if you noticed in the previous lesson, we actually did not explicitly declare our `String` to be of type `String`; since we put the quotation marks around it, Swift automatically knew it was that type!

Now that you've got the basics down, it's time to move on to some fun stuff: functions!

## Recommended book

- [Anyone Can Create an App: Beginning iPhone and iPad Programming by Wendy Wise](https://www.amazon.com/gp/product/1617292656/ref=as_li_qf_sp_asin_il_tl?ie=UTF8&tag=highbrow01-20&camp=1789&creative=9325&linkCode=as2&creativeASIN=1617292656&linkId=beffd3976cf14b8e3dd574ad67df328d)
