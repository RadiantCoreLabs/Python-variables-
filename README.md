📌 Python Variables: Naming Conventions Guide
A beginner-friendly explanation of variable naming styles in Python, including snake_case, camelCase, and PascalCase with examples.

🐍 Variable Naming Conventions
1. snake_case (Recommended in Python)
Use lowercase letters with underscores between words. This is the standard convention in Python (following PEP 8).

python
user_name = "Alice"
max_speed = 100
is_valid = True
2. camelCase (Common in Java/JavaScript)
Start with a lowercase letter, then capitalize the first letter of each subsequent word.

python
userName = "Bob"  
currentScore = 50  
isActive = False  
3. PascalCase (Used for Classes in Python)
Capitalize the first letter of every word (including the first). Used for class names in Python.

python
ClassName = "MyClass"  
HttpRequest = "GET"  
PlayerCharacter = "Warrior"  
❌ Avoid These in Python
UPPERCASE_WITH_UNDERSCORES → Reserved for constants (PI = 3.14).

kebab-case → Not valid in Python (user-name causes syntax errors).

Single letters → Only for trivial cases (i, x in loops).

✅ Best Practices
✔ Use snake_case for variables/functions (calculate_total()).
✔ Use PascalCase for classes (class UserProfile:).
✔ Make names descriptive (e.g., student_count instead of n).

🔗 Resources
PEP 8 – Python Style Guide

Real Python: Naming Conventions
