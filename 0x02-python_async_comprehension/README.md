# Python Async Comprehension
This project focuses on asynchronous programming concepts in Python, specifically asynchronous generators and comprehensions. By completing this project, you will gain a solid understanding of how to write asynchronous code using generators and comprehensions in Python.

## Learning Objectives

By the end of this project, you will be able to:

- Write asynchronous generators to produce data streams asynchronously.
- Utilize async comprehensions to collect data asynchronously.
- Type-annotate coroutines and understand their significance.
- Measure and understand the runtime performance of asynchronous operations.

## Project Structure

This project consists of three tasks:

1. **Async Generator**:
   - Implement a coroutine named `async_generator` that yields random numbers asynchronously.
   - This coroutine loops 10 times, waiting asynchronously for 1 second on each iteration before yielding a random number between 0 and 10.
   - Example usage is provided in `0-main.py`.

2. **Async Comprehensions**:
   - Import the `async_generator` coroutine from the previous task.
   - Write a coroutine named `async_comprehension` to collect 10 random numbers asynchronously using an async comprehension over `async_generator`.
   - Example usage is provided in `1-main.py`.

3. **Run time for four parallel comprehensions**:
   - Import `async_comprehension` from the previous task.
   - Write a coroutine named `measure_runtime` to execute `async_comprehension` four times in parallel using `asyncio.gather`.
   - Measure the total runtime and return it.
   - Example usage is provided in `2-main.py`.

## Requirements

- Python 3.7
- Ubuntu 18.04 LTS
- Pycodestyle (version 2.5.x) for code style enforcement

## Usage

To execute the provided examples, run the respective main files:

```bash
$ ./0-main.py  # For Task 0
$ ./1-main.py  # For Task 1
$ ./2-main.py  # For Task 2
```

Ensure that all Python files are executable (`chmod +x filename.py`) and follow the provided requirements.

## Author

- **Emmanuel Turlay** - Staff Software Engineer at Cruise

## Acknowledgments

- This project is part of the ALX curriculum.

---

Feel free to customize the README further based on your preferences or additional project details.
