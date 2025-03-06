+++
date = '2025-03-06T16:14:09-06:00'
# draft = true
title = 'Adventures with C++: Bitwise Operators'
+++

# Adventures with C++: Bitwise Operators

## Introduction
Today I learned about [bitwise operators](https://en.cppreference.com/w/cpp/language/operator_arithmetic), which are interesting, because they are similar to [arithmetic operators](https://en.cppreference.com/w/cpp/language/operator_arithmetic). There is a bit difference though, instead of manipulating the numbers themselves, bitwise opotators will instead manipulate the bits and bytes used by the numbers.

## Bits and Bytes
To understand how bitwise oporators work, first we need to understand bits and bytes. So, what is a bit? Simply put a bit is a base-2 number, a bit is either on, 1, or off, 0. When you compare it to our base-10 numbering system, we can count from `0 to 9` before having to add an extra column, the "1" in 10. In a base-2 system you only have 0 and 1, so, 0 and 1 will stay as is, but the equivilent of `2`? You're going to have to add a second column, `10`. What about `3`? That's going to be `11`. On `4` we need to add our 3rd column, `100`. Now what are bytes? Bytes are a group of `8 bits`, and based on the instructions given to the computer, it will interprate the bytes a certain way. In this case, we are keeping it simple, we just want to count with bytes. So the number `4` from before if we include all 8 bits in a byte will look like `00000100`. Now that we know how bits and bytes work, what's the largest base-10 number a byte can count to?

## What are Bitwise Operators?
Bitwise operators manipulate the `bits` of a number instead of the number itself. I'll get into how exactly they do this a little later, but first, why is this important? 