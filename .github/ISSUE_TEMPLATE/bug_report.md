---
name: Bug report
about: Report a bug in project unit tests, starter files or other code
title: ''
labels: 'bug'
assignees: ''

---

## Describe the bug
A clear and concise description of what the bug is.  Here are a few ideas.

A copy-paste of a traceback (prefer text, not screenshot)
```console
$ python test.py
  File "test.py", line 2
    print(f"x = {x}")
                   ^
SyntaxError: invalid syntax
```

A quote from the source code of a public unit test.
```python
def test():
    print(f"x = {x}")
```

A quote from the spec
> Be sure to format your strings.

## To Reproduce
Steps to reproduce the behavior.
1. Use a Python f-string in solution code
2. Submit code to the autograder

## Expected behavior
Test should pass without an error about unsupported syntax.
