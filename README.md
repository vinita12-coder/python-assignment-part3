# Part 3: File I/O, APIs & Exception Handling — Product Explorer

A program that reads/writes files, fetches real API data, and handles all errors gracefully.

## Tasks
- **Task 1:** File Read & Write — write, append, read, keyword search on python_notes.txt
- **Task 2:** API Integration — fetch, filter, sort products from DummyJSON API, POST request
- **Task 3:** Exception Handling — safe divide, guarded file reader, robust API calls, input validation loop
- **Task 4:** Logging — timestamped error logger writing to error_log.txt

## Concepts Used
- File I/O: open, read, write, append
- requests library: GET, POST, timeout
- try / except / finally
- Exception types: ZeroDivisionError, TypeError, FileNotFoundError, ConnectionError, Timeout
- datetime for timestamps

## API Used
- https://dummyjson.com (no authentication required)

## How to Run
```bash
pip install requests
python part3_api_files.py
```

## Files
- `part3_api_files.py`
- `python_notes.txt`
- `error_log.txt`
