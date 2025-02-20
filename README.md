# Unhandled Exception in Scala Class

This repository demonstrates a common error in Scala: failing to handle potential exceptions thrown within a class's methods.

The `MyClass` example showcases a setter method (`age_=`) that throws an `IllegalArgumentException` if a negative age is assigned. However, the `Main` object (the main execution point) doesn't include `try-catch` block to handle this exception, resulting in program termination upon encountering a negative age.

The solution demonstrates how to handle the exception using a `try-catch` block in the main execution.