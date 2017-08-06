*If you are reporting a bug, please use the template below and replace italic letters with your input!
Otherwise, just delete it all.*

## Environment
- ObjectBox version (check if you are using the newest version): *?*
- Android version: *?*

## Steps that lead to the bug
### Description
*Describe in words the situation in which you encounter the bug.

Check if you have a stacktrace you can share; if the problem occurs at build time, use `--stacktrace` for the Gradle build (`./gradlew build --stacktrace`). For runtime errors, check Android's Logcat for stacktraces and potential error logs before the issue occured.*
### Trigger code
*Provide the code that triggers a bug.
Ideally, try to keep it short -> try removing as much code as possible while still having the bug happen.*
### Initial state
*Describe the state of the database prior to the trigger code.
You may explain it in words, or even better, provide the code that creates a database with that state.*

## Entities
*Provide the code describing the entities that are involved in the bug.
Skip any generated code.
Feel free to also skip any members that have nothing to do with the ObjectBox, but make sure to include all relevant members and annotations like: relations, id, indexes, ...*

## Other
- [] Is the bug happening inside a transaction?
- [] To what degree does your app run multi-threaded?
- [] Do you use indexes, especially on the queried properties?
- [] Do you use explicit transactions?
- [] Anything else special about your app?
