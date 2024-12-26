# Dart: Handling Empty Lists with reduce()

This example demonstrates a common error encountered when using the `reduce` method in Dart with an empty list. The `reduce` method operates by iteratively applying a function to combine elements of a list. If the list is empty, there are no elements to combine, leading to an exception.

The provided code showcases both correct and incorrect usage, highlighting how to mitigate this potential issue.

## Solution
The solution involves checking if the list is empty before calling `reduce`. If empty, a suitable default value should be returned.  See `bugSolution.dart` for an implementation.