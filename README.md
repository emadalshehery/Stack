# Stack (Interactive Menu)

**Notebook:** `stack.ipynb`

A stack (LIFO) implemented with a Python list and controlled through a text menu.

## Functions

| Function        | Purpose                          |
|-----------------|----------------------------------|
| `createStack()` | Returns a new empty stack `[]`   |
| `push(stack, element)` | Adds an element to the top |
| `pop(stack)`    | Removes and returns the top element |
| `isEmpty(stack)`| `True` if the stack has no elements |

## Menu

| Choice | Action |
|--------|--------|
| 1 | Push an integer entered by the user |
| 2 | Pop the top element (prints "The stack is empty" if none) |
| 3 | End the program |

Any other choice prints `Error` and asks again. The current stack is printed before every prompt.

## Sample Run

```
push 10 -> [10]
push 23 -> [10, 23]
pop     -> 23, stack is [10]
end     -> End of program
```

## Run

```bash
jupyter notebook stack.ipynb
```

Only the Python standard library is needed.
