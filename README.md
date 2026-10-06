# 🐻 C# Buddy — Learn C# by Levels

A beginner-friendly C# learning website designed like a small learning game.

## Course structure

The course starts extremely easy and unlocks one level at a time:

1. **Say Hello** — your first `Console.WriteLine`
2. **Change the Message** — print different text
3. **Your First Variable** — store text in a `string`
4. **Numbers** — use `int`
5. **Ask the User** — read input
6. **Make a Decision** — `if` / `else`
7. **Repeat With a Loop** — `for`
8. **Build a Method** — methods and parameters
9. **Collections** — arrays and `foreach`
10. **Classes** — your first object blueprint
11. **Handle Errors** — `try` / `catch`
12. **Final Project** — number guessing game

Every level includes:
- a simple goal
- step-by-step instructions
- a worked example
- one small exercise
- a hint
- an answer checker
- level unlocking/progression

## GitHub Pages structure

Put these files directly in the repository root:

```text
csharp-buddy/
├── index.html
├── style.css
├── script.js
├── mascot.png
├── .nojekyll
└── README.md
```

Then enable GitHub Pages:

**Settings → Pages → Deploy from a branch → main → / (root) → Save**

## Important

The exercise checker is a browser-side learning aid. It checks whether the submitted code contains the expected structure; it does not compile or execute arbitrary C# in the browser.

For real C# execution, use the .NET SDK/Visual Studio/VS Code or connect this frontend to a secure code-execution backend later.
