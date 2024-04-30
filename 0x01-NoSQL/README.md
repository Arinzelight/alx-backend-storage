# NoSQL

## Introduction

This project aims to provide a comprehensive understanding of NoSQL databases, particularly focusing on MongoDB. NoSQL databases offer flexible schemas and are suitable for handling large volumes of unstructured data, making them a popular choice for modern applications.

this project covers various aspects of NoSQL databases, including their differences from SQL databases, types of NoSQL databases, benefits, querying, and manipulation of data using MongoDB.

## Learning Objectives


- Define what NoSQL means and its significance in modern database systems.
- Differentiate between SQL and NoSQL databases in terms of data model, scalability, and use cases.
- Understand the ACID properties (Atomicity, Consistency, Isolation, Durability) and their relevance in database systems.
- Explain document storage and its characteristics, including schema flexibility and horizontal scalability.
- Identify different types of NoSQL databases, such as document-oriented, key-value, column-family, and graph databases.
- Discuss the benefits of using a NoSQL database, including high scalability, performance, and flexibility.
- Query information from a NoSQL database using MongoDB's query language.
- Perform data manipulation operations, including insertion, updating, and deletion, in MongoDB.
- Use the PyMongo library to interact with MongoDB from Python applications.

## Installation Guide

### Install MongoDB 4.2 on Ubuntu 18.04

Follow these steps to install MongoDB 4.2 on Ubuntu 18.04:

1. Import the MongoDB GPG key:

    ```bash
    wget -qO - https://www.mongodb.org/static/pgp/server-4.2.asc | sudo apt-key add -
    ```

2. Add the MongoDB repository to your package sources:

    ```bash
    echo "deb [ arch=amd64,arm64 ] https://repo.mongodb.org/apt/ubuntu bionic/mongodb-org/4.2 multiverse" | sudo tee /etc/apt/sources.list.d/mongodb-org-4.2.list
    ```

3. Update the package lists:

    ```bash
    sudo apt-get update
    ```

4. Install MongoDB:

    ```bash
    sudo apt-get install -y mongodb-org
    ```

### Check MongoDB Installation

Check the status of MongoDB service:

```bash
sudo service mongod status

