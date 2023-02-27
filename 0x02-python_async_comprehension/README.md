# 0x02. Python - Async Comprehension
<img src="https://dev.to/social_previews/article/225164.png" width="600px"/>
Project done during ALX Software Engineering Scholarship 2022 at Alx Students Education. It aims to learn about:
* How to write an asynchronous generator
* How to use async comprehensions
* How to type-annotate generators

## Resources
Read or watch:

* [PEP 530 – Asynchronous Comprehensions](https://peps.python.org/pep-0530/)
* [What’s New in Python: Asynchronous Comprehensions / Generators](https://www.blog.pythonlibrary.org/2017/02/14/whats-new-in-python-asynchronous-comprehensions-generators/)
* [Type-hints for generators](https://stackoverflow.com/questions/42531143/how-to-type-hint-a-generator-in-python-3)

## Technologies
* Ubuntu 18.04 LTS using python3 (version 3.7) with pycodestyle style (version 2.5.x)

## Files
|Script|Description|
|-----------|-------------------------|
|`0-async_generator.py`| A script that coroutine called `async_generator` that takes no arguments.The coroutine will loop 10 times, each time asynchronously wait 1 second, then yield a random number between 0 and 10. Use the random module.|
|`1-async_comprehension.py`|A script that collect 10 random numbers using an async comprehensing over `async_generator`, then return the 10 random numbers.|
|`2-measure_runtime.py`|A script import `async_comprehension` from the previous file and write a `measure_runtime` coroutine that will execute async_comprehension four times in parallel using `asyncio.gather`.|
