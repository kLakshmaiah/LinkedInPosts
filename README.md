# Discard Patterns (`_`) in C#

Ever come across the underscore (`_`) in C# and wondered what it does? It's not just a variable name—it's a **discard pattern** that helps write cleaner, more efficient code! 🚀

## 🔹 What is a Discard?

A **discard** (`_`) is a placeholder that tells the compiler, *"I'm intentionally ignoring this value."* It improves readability and avoids unnecessary variable allocations.

## 🔹 Introduced in C# 7.0

The discard pattern was introduced in **C# 7.0** and has since been enhanced in later versions.

## 🔹 Where Can You Use It?

### Ignoring Unused Return Values

![TryParse Discard](/tryparsediscard.png)

Instead of creating a useless variable for `out`, we discard it!

### Deconstructing Tuples

![Tuple Discards](./Tupple-Discard-Patterns.png)

We discard the middle values since we don't need them.

### Switch Expressions

![Switch Discard Patterns](/Discard-Patterns.png)

Here, `_` acts as a default case for switch.

## 🚀 Why Use Discards?

- **✔ Improves Readability**
- **✔ Reduces Unnecessary Variables Usage**
- **✔ Enhances Code Clarity**

Next time you see `_`, don't ignore it—embrace it! 😃

Have you used discard patterns in your projects? Share your experience! ⬇

#CSharp #DotNet #CodingTips
