# Topic 04: Types and Branches (Conditionals)

**Week 2 | CIS Intro to Programming**

---

## Overview

This week you will practice using conditionals (`if`/`elif`/`else`) to make decisions in your program. Use the starter code as a jumping-off point and extend it in your own direction.

## Assignment Prompt

Starting from the starter code below, build a simple decision-making program. Your finished program should:

- Accept at least one input from the user (using `input()`)
- Use at least two conditional branches (`if`/`elif`/`else`) to respond differently based on that input
- Print a clear, human-readable result for each possible path through your program
- Handle at least one type conversion (e.g., converting input to an `int` or `float`)

## Starter Code

Copy the code below into a file named `solution.py` in your forked repository.

```python
# Topic 04 Collaborative Assignment
# Your Name:
# Date:

# --- STARTER CODE ---
# This starter program checks if a temperature is hot, warm, or cold.
# Extend it, change the theme, or use it as inspiration for your own idea.

temp_input = input("Enter a temperature in Fahrenheit: ")
temperature = float(temp_input)

if temperature >= 90:
    print("It is hot outside.")
elif temperature >= 60:
    print("It is warm outside.")
else:
    print("It is cold outside.")

# --- YOUR EXTENSION BELOW THIS LINE ---
# Ideas: Add more conditions, change the topic entirely,
# or add a second input and a second set of branches.
```

## Peer Review Prompt

When reviewing a classmate's code this week, consider:

- Are their conditional branches easy to follow?
- Did they handle all the cases they needed to?
- Is there an edge case (like a very large or very small number, or unexpected input) that their code might not handle?

## Submission Instructions

1. Fork this repository into your own GitHub account.
2. Write your code and commit it to your fork.
3. Submit your repo link using the **Submit Your Repo Link** form in Blackboard.
4. Open the **Class Repo Directory** in Blackboard and find two classmates' repos.
5. Leave a GitHub Issue on each with substantive feedback using the peer review prompt above as your guide.

## Notes

Feel free to change the theme of the starter program entirely. The weather example is just a scaffold. Your program can be about anything — grade categories, fitness zones, a simple quiz, or something else you find interesting.
