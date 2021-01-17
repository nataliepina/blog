---
title: 'What is a Scalar Primitive?'
author: [Natalie Pina]
tags: ["Code", "primitives", "javascript", "data", "primitives", "scalar primitive", "primitive data types", "JS"]
image: img/artem-sapegin-b18TRXc8UPQ-unsplash.jpg
date: '2021-01-16T10:00:00.000Z'
draft: false
---

# Scalar Primitives 

Perhaps you have heard of primitives in JavaScript but have you heard of these values referred to as scalar primitives? Let’s do a quick deep dive on what a scalar primitive is and if there is a distinction between the two.

I had first heard the reference to a "scalar primitive" when reading Kyle Sympson’s _You Don’t Know JS_ -- which I highly recommend for anyone who’d like to get into the nuts and bolts of JavaScript. 
Here is the free reference: [You Don't Know JS](https://github.com/getify/You-Dont-Know-JS/blob/1st-ed/types%20%26%20grammar/ch3.md) 

During a [Javascript Book Club](https://www.madisonkanna.com/join-our-javascript-book-club/) meet-up
, a few other developers including myself brought up the conversation of "scalar primitives" questioning the terminology. Let's take a look together at the termonology and clear up some naming conventions. 

## What does ‘scalar’ even mean?
According to [Merriam-Webster](https://www.madisonkanna.com/join-our-javascript-book-club/):
```
Definition of scalar (adjective)
1: having an uninterrupted series of steps. 
2: capable of being represented by a point on a scale
```

It accurate for us to think of _scalar_ as a point on a scale (or point of data). In simpler terms, _scalar_ means a single value.

## Summarizing Notes:
- Most important to note, in JavaScript the “scalar primitive values” are immutable. (Immutable means after a value type has been set in memory it cannot be mutated/modified/changed.)

- Arrays and Objects are not scalar as they are comprised of multiple values/units of data. These are known as _compound values_.

- Scalar primitives are always assigned and passed by value-copy, not by referrence. 

- Our "primitive" values are really the same as _scalar primitives_ as they are single units of data that are immutable. Scalar is simply an add-on adjective that helps to describe the intended behavior of these values.


## Scalar Primitive Values
- Null
- Undefined
- Boolean
- Number (including BigInt)
- String
- Symbol (ES6)


### Primimtives vs. Natives
One last mention that may clear up some confusion is to discuss the distinction between 'primitives' and 'natives'. I suggest reading Ch. 3 within Types & Grammer - _You Don't Know JS_ to go in-depth on natives and primitives.

### The End
In conclusion, _scalar primitive values_ are our immutable/single values within JavaScript's native data types. They include: null, undefined, boolean, number, string and symbol. I hope this article provided you with some clarity of a scalar primitive. 



Cover Photo Credit: [Artem Sapegin](https://unsplash.com/@sapegin?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)