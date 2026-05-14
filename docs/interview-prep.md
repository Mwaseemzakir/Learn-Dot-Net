# .NET Interview Preparation

Resources to help you prepare for .NET developer interviews.

## Topics to Master

### C# Fundamentals
- Value types vs reference types
- Stack vs heap memory allocation
- Boxing and unboxing performance implications
- `readonly` vs `const` — when to use each
- `ref`, `out`, and `in` parameters
- Delegates, events, Func, Action, and lambda expressions
- Extension methods
- LINQ — query syntax vs method syntax
- Generics, constraints, and covariance / contravariance
- Pattern matching and switch expressions (C# 7+)

### Object-Oriented Programming
- SOLID principles with real C# examples
- Common design patterns — Singleton, Factory, Repository, Strategy, Decorator
- Inheritance vs composition — when to prefer each
- Interface vs abstract class
- Dependency inversion and dependency injection

### ASP.NET Core
- Middleware pipeline and the importance of order
- Dependency injection lifetimes — Transient, Scoped, Singleton — and gotchas
- Action filters and result filters
- Routing — conventional vs attribute routing
- Model binding and validation
- JWT authentication and authorization
- Minimal APIs vs controllers — trade-offs

### Entity Framework Core
- Eager vs lazy vs explicit loading
- Migrations workflow — Add, Update, Revert
- The N+1 query problem and how to solve it
- Change tracking behavior — AsNoTracking
- Executing raw SQL safely with `FromSqlRaw`

### Async & Concurrency
- `Task` vs `ValueTask` — when each is appropriate
- `async void` anti-pattern and why it is dangerous
- `ConfigureAwait(false)` — what it does and when to use it
- How deadlocks occur in async code and how to prevent them
- `CancellationToken` usage and cooperative cancellation
- `IAsyncEnumerable<T>` and async streams

## Online Resources

1. [C# and .NET Interview Questions — CodeMaze](https://code-maze.com/net-interview-questions/)

	Practical .NET interview questions with detailed answers covering all experience levels.

2. [LeetCode](https://leetcode.com/)

	Practice data structures and algorithms problems commonly asked in technical interviews. C# is a supported language.

3. [NeetCode](https://neetcode.io/)

	Curated roadmap and video explanations for coding interview patterns, with solutions available in C#.

4. [Top-Voted C# Questions on Stack Overflow](https://stackoverflow.com/questions/tagged/c%23?sort=votes)

	Top-voted C# questions — a great way to discover common pitfalls and edge cases.

5. [Microsoft .NET Documentation](https://learn.microsoft.com/en-us/dotnet/)

	The definitive reference for understanding how .NET actually works — invaluable for deep technical interviews.
