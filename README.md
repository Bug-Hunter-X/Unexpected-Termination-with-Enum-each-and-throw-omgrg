This example demonstrates a common issue in Elixir when using `Enum.each` with `throw`. The `throw` statement immediately exits the `Enum.each` loop and propagates the exception up the call stack, preventing subsequent code from executing.  This can lead to unexpected behavior if not handled correctly.

The solution shows how to use `try-catch` to handle the thrown exception and control the program flow gracefully.