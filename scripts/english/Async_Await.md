# Async & Await
Async and await make writing asynchronous code easier, allowing non-blocking tasks.

## Writing Asynchronous Functions:
Use ```async``` and ```await``` to run tasks concurrently.

Example:
```python
import asyncio

async def fetch_data():
    await asyncio.sleep(1)
    return "Data fetched"

asyncio.run(fetch_data())
