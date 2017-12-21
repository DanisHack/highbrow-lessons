# Episode #6 of 10 - Swift 3 Arrays

![](https://4cawmi2va33i3w6dek1d7y1m-wpengine.netdna-ssl.com/wp-content/uploads/2017/06/6-4.jpg)

You're a busy person. So busy, in fact, you even have to schedule when you go to the supermarket! You spot an open window of time on a Wednesday afternoon and ask yourself, "What do I need to buy?"

You open the fridge and begin taking notes on your phone.

- Eggs
- Cheese
- Bread
- Beer

Breakfast of champions! You're all ready for your supermarket run and have actually accomplished two things. First, you made your grocery list in record-breaking time, and second, you made an array! Believe it or not, you have been making arrays your entire life.

## Code

So, what exactly is an array? An array basically holds a list of elements of the same type. For example, if we were to write an array of our grocery list items in the example above, the code might look something like this:

```swift
var groceryListItems = ["Eggs", "Cheese", "Bread", "Beer"]
```

Notice how we put quotations around each item? That's because they are all of type **String**, as you learned in Lesson 2. All items in arrays must be of the same value type. For example, we couldn't have an array that held these values:

```swift
var badArray = ["Eggs", 7]
```

Also, notice the syntax! Arrays are created by placing items of the same value type within brackets. You could also explicitly state the value types in the syntax as such:

```swift
var listItems: [String] = ["Eggs", "Cheese", "Bread", "Beer"]
```

What we're doing here is creating the variable listItems and telling the program that this array will hold values of type `String` with the syntax `: [String]`, followed by the array of items. It's also important to note that items in arrays are separated by a comma.

## Tying It into the Big Picture

Why is this important? Who cares if we can throw items into a list? If you recall our previous lessons, we were creating one variable at a time and assigning it a value. But what happens if you needed multiple values assigned to one variable? A real-world example of this could be a friends list in a social media app. Would you want to have to create a new variable for every friend you add? And then generate a new name for that variable? It would be insane! Instead, you could have one *array* called `addedFriends` and store all your friends in there. As you dive into the world of programming, you will find that you can do so many cool things with arrays, like order them in certain ways, find specific items, add and subtract items from the list, and so much more!

## Recommended book

- [iOS Apps for Masterminds, 2nd Edition: How to Take Advantage of Swift 3 to Create Insanely Great Apps for iPhones and iPads by J D Gauchat](https://www.amazon.com/gp/product/1537517880/ref=as_li_qf_sp_asin_il_tl?ie=UTF8&tag=highbrow01-20&camp=1789&creative=9325&linkCode=as2&creativeASIN=1537517880&linkId=44943c815a6312916d09fe59436b9f58)
