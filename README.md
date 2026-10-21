# Python Quiz Program
A simple Python program that validates student ID and answers.
## Code
```python
def quiz():
    id = input("Enter your ID: ")
    if not id.isdigit():
        print("Invalid ID")
        return
    answer = input("Enter answer: ").upper()

    if answer not in "ABCD":
        print("Invalid answer")
        return

    print("checked")
quiz()
```
## Team Members
- @TalaFahad1
- @Aljowharah67
- @Janoo15
- @LeenAlhossan
