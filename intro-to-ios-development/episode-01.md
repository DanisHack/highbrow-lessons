# Episode #1 of 10 - Variables

![](https://4cawmi2va33i3w6dek1d7y1m-wpengine.netdna-ssl.com/wp-content/uploads/2017/06/1-5.jpg)

When I was 12, my mom threw a party at our house with all her friends. She bought so much food and drinks, it looked like we had robbed a Costco. As people started to trickle in, they started to grab some drinks and appetizers, and as a kid, that was my cue to go upstairs and let the adults party.

Around an hour later, I was getting thirsty and started craving a soda. I briskly ran downstairs, grabbed a drink from the soda bucket without looking, and sprinted back up to my room. I glanced at what I had picked out and realized it was some kind of juice I had never heard of before. It turned out to be pretty good!

An hour went by, and I was feeling a little dizzy and flushed. I read the back label of the juice I was drinking, and it turned out to be a wine cooler! This isn't good, I thought, and then proceeded to take the best nap a 12-year-old could imagine.

**The moral of the story:** Not all drink buckets are filled with just soda. But what does this have to do with code?

## Code

In programming, we have something called a variable. Just like using words to write a book or tell a story, variables are used to define certain elements that you're working with. You can think of variables as buckets with a label on each one to define what's supposed to go in it. For example, if you were hosting the party in the above story and had a bucket labeled "sodas," you could put a variety of sodas into that bucket so long as they were, in fact, soda (lesson learned).

Therefore, the variable in this scenario could be reduced to the following sentence:

There is a **bucket** (variable) labeled **soda** (type) with **Coke** (value) in it.

In other words:

```swift
var bucket: soda = coke
```
Because we declared what can go in the bucket with `bucket: soda`, we could put any other sodas in place of the value, like so:

```swift
var bucket: soda = sprite
var bucket: soda = root beer
```

However, if we threw a **wine cooler** in the bucket, we would get an error:

```swift
var bucket: soda = wine cooler // Error! Wine coolers aren't soda! What if a 12-year-old kid drinks it?!
```

Notice how we put `var` in front of "bucket"? When we do this, we are **declaring** or creating the bucket. Once we've declared it, we can simply reference its name the next time we want to change or use the item. It's just like meeting someone for the first time. You introduce yourself with "Hi, my name is Jim," but you wouldn't start every sentence afterward stating your name.

Imagine the following scenario:

> Mother: Evan, can you please fill the bucket with Sprite?

> Evan: Okay!

```swift
var bucket: soda = sprite
```

> Mother: I changed my mind, can you fill it with Coke, please?

```swift
bucket = coke
```
Once we declared the bucket of soda, we didn't have to do it again afterward. We could simply change the contents—hence the name **variable**!

## Tying It into the Big Picture

Unfortunately, we can't throw this **directly** into a codebase just yet, but the syntax is what's important here. All code, at the end of the day, is putting items into buckets and telling those buckets to do specific things. Just by understanding this simple concept, you're well on your way to writing your first program.

## Recommended book

- [Learning Swift: Building Apps for macOS, iOS, and Beyond by Paris Buttfield-Addison, Jon Manning, Tim Nugent](https://www.amazon.com/gp/product/1491967064/ref=as_li_qf_sp_asin_il_tl?ie=UTF8&tag=highbrow01-20&camp=1789&creative=9325&linkCode=as2&creativeASIN=1491967064&linkId=d3450f0a776ba3cb3a37cd6dd1a06365)
