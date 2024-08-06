# Mastering Asynchronous Comprehensions in Python 3

## Project Overview

This project delves into asynchronous programming in Python 3, emphasizing the powerful concept of asynchronous comprehensions. You'll build a set of scripts designed to demonstrate the creation and utilization of asynchronous generators and comprehensions for efficient, concurrent code.

## Tasks

**0. async_generator:**

- File: `0-async_generator.py`
- Description: Implement an asynchronous coroutine named `async_generator`. This coroutine will loop 10 times, asynchronously waiting 1 second each iteration before yielding a random number (0-10).  The `random` module will be used to generate these numbers.

**1. async_comprehension:**

- File: `1-async_comprehension.py`
- Description: Create a coroutine called `async_comprehension` that utilizes the `async_generator` from the previous task. This new coroutine will gather 10 random numbers using an asynchronous comprehension and return them as a list.

**2. measure_runtime:**

- File: `2-measure_runtime.py`
- Description: Implement a coroutine named `measure_runtime`. It will leverage `asyncio.gather` to execute `async_comprehension` four times in parallel.  The coroutine will then measure and return the total runtime required for these parallel executions.

## Key Concepts

- **Asynchronous Programming:**  Learn how to write non-blocking code in Python to enhance responsiveness and efficiency.
- **Asynchronous Generators:** Understand how to create iterators that yield values asynchronously.
- **Asynchronous Comprehensions:** Discover a concise way to work with asynchronous generators, collecting results within a list.
- **asyncio.gather:** Explore how to run multiple coroutines concurrently.
