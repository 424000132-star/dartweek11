# Week 11: Asynchronous Programming in Dart

## Description
A simple Dart program demonstrating:
- Classes and objects
- Inheritance with `Manager` and `Developer`
- Method overriding
- Asynchronous programming using `Future`, `async`, and `await`
- A simulated database save operation

## Files
- `main.dart` — source code for the program.

## How to Run
How to Run Open https://dartpad.dev/

```bash
dart run main.dart
```

## Sample Output
```text
Employee #101: Piollo
  Manages a team of 5
Employee #102: Lexxine
  Writes Dart

Starting save for Piollo...
  [saveRecord] Saving Piollo to the database...
This prints immediately, before the result is ready.
Result: Record for Piollo (ID 101) saved successfully.

Starting save for Lexxine...
  [saveRecord] Saving Lexxine to the database...
Result: Record for Lexxine (ID 102) saved successfully.

All done.
```

Note: Each simulated save waits about 2 seconds before returning its result.
