# MongoDB Fundamentals Assignment

This project demonstrates basic and advanced MongoDB operations using Node.js and the MongoDB Shell.

## Prerequisites

- [Node.js](https://nodejs.org/) installed on your computer
- [MongoDB Community Edition](https://www.mongodb.com/try/download/community) installed and running locally (or a MongoDB Atlas cluster)
- [npm](https://www.npmjs.com/) (comes with Node.js)
- [MongoDB Shell (mongosh)](https://www.mongodb.com/try/download/shell) installed

---

## 1. Running [`insert_books.js`](./insert_books.js)

This script populates your MongoDB database with sample book data.

### Steps:

1. **Install dependencies**  
   Open your terminal in this project folder and run:
   ```
   npm install mongodb
   ```

2. **Start MongoDB**  
   Make sure your MongoDB server is running locally (default: `mongodb://localhost:27017`).

3. **Run the script**  
   In your terminal, execute:
   ```
   node insert_books.js
   ```
   This will insert the sample books into the `plp_bookstore` database, `books` collection.

---

## 2. Running the queries in [`queries.js`](./queries.js)

This file contains MongoDB queries for CRUD, advanced queries, aggregation, and indexing.

### Steps:

1. **Open MongoDB Shell**  
   In your terminal, start the MongoDB shell by typing:
   ```
   mongosh
   ```

2. **Switch to the correct database**  
   In the shell, run:
   ```
   use plp_bookstore
   ```

3. **Run the queries**  
   - You can copy and paste queries from [`queries.js`](./queries.js) directly into the shell.
   - Each query will operate on the `books` collection you populated earlier.

---

## Notes

- If you want to reset the data, simply re-run [`insert_books.js`](./insert_books.js).
- You can use [MongoDB Compass](https://www.mongodb.com/products/compass) for a graphical interface to view your data.

---

## Files

- `insert_books.js` &mdash; Populates the database with sample data.
- `queries.js` &mdash; Contains all required MongoDB queries for the assignment.

---