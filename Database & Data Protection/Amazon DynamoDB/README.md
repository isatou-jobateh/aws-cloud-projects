# Introduction to Amazon DynamoDB

## Overview

This project documents my hands-on experience with **Amazon DynamoDB**, a fully managed NoSQL database service provided by AWS.

In this lab, I created and worked with a DynamoDB table designed to store information for a music library. I practiced creating a table, adding items, querying data, and deleting the table after completing the exercise.

## AWS Service

* **Amazon DynamoDB**

## Lab Information

* **Lab:** Introduction to Amazon DynamoDB
* **Platform:** AWS Skill Builder
* **Duration:** 45 minutes
* **Type:** Hands-on lab
* **Environment:** AWS Skill Builder lab environment

## Learning Objectives

After completing this lab, I was able to:

* Create an Amazon DynamoDB table
* Add data to a DynamoDB table
* Query a DynamoDB table
* Delete a DynamoDB table

## What I Learned

### 1. DynamoDB Tables

DynamoDB stores data in tables. Unlike relational databases, DynamoDB does not require a traditional table structure with fixed rows and columns.

Instead, data is stored as **items**, and each item contains **attributes**.

### 2. Items and Attributes

An **item** is a single record in a DynamoDB table.

An **attribute** is a piece of information contained within an item.

For example, a music library could contain information such as:

* Artist
* Song title
* Album
* Genre

### 3. Primary Key

DynamoDB uses a primary key to uniquely identify items within a table.

The primary key allows DynamoDB to efficiently locate and retrieve individual items.

### 4. Adding Data

I practiced adding items to the DynamoDB table and storing information about the music library.

### 5. Querying Data

I used DynamoDB to query information stored in the table.

Queries allow applications to retrieve specific items based on the table's key structure.

### 6. Deleting a Table

After completing the exercise, I deleted the DynamoDB table as part of the lab cleanup process.

## Lab Tasks

### Task 1: Create a New Table

Created a DynamoDB table for the music library.

### Task 2: Add Data

Added music-related data to the DynamoDB table as items.

### Task 3: Query Data

Queried the DynamoDB table to retrieve stored information.

### Task 4: Delete the Table

Deleted the DynamoDB table after completing the lab.

## Evidence

Screenshots from the completed AWS Skill Builder lab are included in this folder.

Structure:

```text
Amazon DynamoDB/
├── README.md
├── DynamoDB~Certificate
└── DynamoDB~Lab~Screenshots/
    ├── 01-create-table.png
    ├── 02-add-data.png
    ├── 
    ├── 03-query-data.png
    └── 04-delete-table.png
```

## Key Takeaways

Through this lab, I gained practical experience with:

* Amazon DynamoDB
* NoSQL databases
* DynamoDB tables
* Items and attributes
* Primary keys
* Adding and querying data
* AWS console-based database management
* Cleaning up AWS resources after completing a lab

## Project Status

**Completed — Hands-on AWS Skill Builder Lab**

This project was completed in an AWS Skill Builder lab environment. The resources used for the exercise were created specifically for the lab and were cleaned up after completion.
