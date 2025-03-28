![Discard-Patterns](https://github.com/user-attachments/assets/e4e6d901-c4e8-4b35-8f59-de5a67a45b9c)# Discard Patterns (`_`) in C#

Ever come across the underscore (`_`) in C# and wondered what it does? It's not just a variable name—it's a **discard pattern** that helps write cleaner, more efficient code! 🚀

## 🔹 What is a Discard?

A **discard** (`_`) is a placeholder that tells the compiler, *"I'm intentionally ignoring this value."* It improves readability and avoids unnecessary variable allocations.

## 🔹 Introduced in C# 7.0

The discard pattern was introduced in **C# 7.0** and has since been enhanced in later versions.

## 🔹 Where Can You Use It?

### Ignoring Unused Return Values
![tryparsediscard](https://github.com/user-attachments/assets/527e35af-e3e9-4e5c-8719-4205148d0140)

Instead of creating a useless variable for `out`, we discard it!

### Deconstructing Tuples
<img src="https://github.com/user-attachments/assets/3130be9f-ba1c-4176-9a39-3b415a26d1d7" alt="Discard-Patterns" width="400">


We discard the middle values since we don't need them.

### Switch Expressions

![Discard-Patterns](https://github.com/user-attachments/assets/8be198b6-1001-403c-a620-0b510666f159)

Here, `_` acts as a default case for switch.

## 🚀 Why Use Discards?

- **✔ Improves Readability**
- **✔ Reduces Unnecessary Variables Usage**
- **✔ Enhances Code Clarity**

Next time you see `_`, don't ignore it—embrace it! 😃

Have you used discard patterns in your projects? Share your experience! ⬇

#CSharp #DotNet #CodingTips
