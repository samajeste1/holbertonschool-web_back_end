# NoSQL - MongoDB

This project covers the fundamentals of NoSQL databases, specifically MongoDB, including basic operations and Python integration with PyMongo.

## Learning Objectives

- What NoSQL means
- Difference between SQL and NoSQL
- What is ACID
- What is document storage
- NoSQL types
- Benefits of a NoSQL database
- How to query information from a NoSQL database
- How to insert/update/delete information from a NoSQL database
- How to use MongoDB

## Requirements

### MongoDB Command File
- All files interpreted/compiled on Ubuntu 20.04 LTS using MongoDB (version 4.4)
- All files should end with a new line
- The first line of all files should be a comment: `// my comment`
- Files will be tested using `wc`

### Python Scripts
- All files interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.9) and PyMongo (version 4.8.0)
- All files should end with a new line
- The first line of all files should be exactly `#!/usr/bin/env python3`
- Code should use the pycodestyle style (version 2.5.*)
- All modules should have documentation
- All functions should have documentation
- Code should not be executed when imported (by using `if __name__ == "__main__":`)

## Tasks

0. **0-list_databases** - List all databases in MongoDB
1. **1-use_or_create_database** - Create or use the database my_db
2. **2-insert** - Insert a document in the collection school
3. **3-all** - List all documents in the collection school
4. **4-match** - List all documents with name="Holberton school"
5. **5-count** - Display the number of documents in the collection school
6. **6-update** - Add a new attribute to documents in the collection school
7. **7-delete** - Delete all documents with name="Holberton school"
8. **8-all.py** - Python function that lists all documents in a collection
9. **9-insert_school.py** - Python function that inserts a new document
10. **10-update_topics.py** - Python function that changes all topics of a school document
11. **11-schools_by_topic.py** - Python function that returns schools having a specific topic
12. **12-log_stats.py** - Python script that provides stats about Nginx logs
