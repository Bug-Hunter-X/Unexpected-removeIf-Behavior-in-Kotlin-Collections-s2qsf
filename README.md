# Kotlin Collection removeIf() Gotcha

This repository demonstrates a subtle but potentially problematic behavior of the `removeIf()` function in Kotlin when applied to different collection types (Lists, Sets, and Maps). While it generally works as expected, the interaction with iterators can lead to unexpected results if not carefully considered.

## The Issue

The `removeIf()` function modifies the collection in-place, removing elements that satisfy the given predicate. However, the exact behavior might subtly vary between Lists, Sets, and Maps, potentially causing confusion or bugs in your code.

## Example

The `bug.kt` file contains code showcasing the differences in behavior between Lists, Sets, and Maps when using `removeIf()`.

## Solution

The `bugSolution.kt` file (optional) could offer a solution or best practice to work around potential issues.
