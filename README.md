# Unhandled JSON Property Access in Dart

This repository demonstrates a common error in Dart when handling JSON responses: attempting to access a property that might not exist in a JSON object.  This can lead to runtime exceptions if not handled properly.

The `bug.dart` file shows the problematic code.  The `bugSolution.dart` file presents a corrected version using the null-aware operator (`?.`) for safe property access.  Consider using a more robust JSON parsing library if you need more comprehensive validation and error handling.