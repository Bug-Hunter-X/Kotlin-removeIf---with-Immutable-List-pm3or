# Kotlin removeIf() with Immutable List
This code demonstrates an uncommon error in Kotlin that arises when using the `removeIf()` function with an immutable list. The `removeIf()` function modifies the list in place, so it can only be used with mutable lists.  Attempting to use it with an immutable list (created using `listOf()`) will result in a compilation error.

The `bug.kt` file shows the error, while `bugSolution.kt` provides a corrected approach using a mutable list.