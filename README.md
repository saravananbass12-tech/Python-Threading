# Python Threading

## Overview

This project demonstrates threading concepts in Python using the `threading` module.

## Topics Covered

* Single-Level Thread
* Multiple Threads
* Daemon Thread

## Technologies Used

* Python
* Threading Module

## Example

```python
import threading as t

def author(n):
    print("Author Name:", n)

t1 = t.Thread(target=author, args=("Saravanan",))
t1.start()
t1.join()
```

## How to Run

```bash
python "-Thread-.py"
```

## Author

**SARAVANAN D**

GitHub: [saravananbass12-tech](https://github.com/saravananbass12-tech)
