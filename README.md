# Nick Chapsas

Each section will include useful pointers (or not)

## Stop Using Booleans in Your Code! | Code Cop #022

:x: Nope

When: 2 October 2024

## The Correct Way to Delete Data in .NET

:white_check_mark: Great

Don't actually delete data from a database, just mark it as deleted and have the reader take care of the details.

Add `IsDeleted` flag and `DeletedAtUtv` (nullable)

When: 2 October 2024