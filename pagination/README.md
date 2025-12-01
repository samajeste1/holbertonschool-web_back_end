# Pagination

This project implements various pagination techniques for datasets in Python.

## Description

This project explores different approaches to paginating large datasets:
- Simple pagination with page and page_size parameters
- Hypermedia pagination with metadata
- Deletion-resilient pagination

## Learning Objectives

- How to paginate a dataset with simple page and page_size parameters
- How to paginate a dataset with hypermedia metadata
- How to paginate in a deletion-resilient manner

## Requirements

- Python 3.9
- Ubuntu 20.04 LTS
- pycodestyle 2.5.*

## Files

- `0-simple_helper_function.py`: Helper function to calculate pagination indexes
- `1-simple_pagination.py`: Simple pagination implementation
- `2-hypermedia_pagination.py`: Pagination with hypermedia metadata
- `3-hypermedia_del_pagination.py`: Deletion-resilient pagination
- `Popular_Baby_Names.csv`: Dataset for testing

## Usage

### Task 0: Simple Helper Function

```python
index_range = __import__('0-simple_helper_function').index_range

res = index_range(1, 7)
print(res)  # (0, 7)

res = index_range(page=3, page_size=15)
print(res)  # (30, 45)
```

### Task 1: Simple Pagination

```python
Server = __import__('1-simple_pagination').Server

server = Server()
print(server.get_page(1, 3))
print(server.get_page(3, 2))
```

### Task 2: Hypermedia Pagination

```python
Server = __import__('2-hypermedia_pagination').Server

server = Server()
print(server.get_hyper(1, 2))
```

### Task 3: Deletion-Resilient Pagination

```python
Server = __import__('3-hypermedia_del_pagination').Server

server = Server()
server.indexed_dataset()
print(server.get_hyper_index(3, 2))
```

## Author

Holberton School Project
