# Books REST API

A simple RESTful API to manage a list of books using Node.js and Express.  
This API supports CRUD operations and stores data in-memory (no database).

---

## Features

- Get all books  
- Get a book by ID  
- Add a new book  
- Update an existing book  
- Delete a book  

---

## Getting Started

### Prerequisites

- Node.js installed ([Download Node.js](https://nodejs.org/))  
- npm (comes with Node.js)  
- Postman or any REST client to test API endpoints  

---

### Installation

1. Clone the repository or download the code files.  
2. Open a terminal and navigate to the project folder.  
3. Run the following commands:

```bash
npm install
node server.js
```

4. The server will start running on port `3000`.

---

## API Endpoints

| Method | Endpoint          | Description           | Request Body (JSON)                  |
|--------|-------------------|-----------------------|------------------------------------|
| GET    | `/books`          | Get all books         | —                                  |
| GET    | `/books/:id`      | Get a book by ID      | —                                  |
| POST   | `/books`          | Add a new book        | `{ "title": "Book Title", "author": "Author Name" }` |
| PUT    | `/books/:id`      | Update a book by ID   | `{ "title": "New Title", "author": "New Author" }` (any or both fields optional) |
| DELETE | `/books/:id`      | Delete a book by ID   | —                                  |

---

## Testing

Use Postman, Insomnia, curl, or your preferred REST client to test the API endpoints.


---

## Notes

- Data is stored in-memory. Restarting the server will reset the book list.
- This is a simple demo project for learning purposes.

---

## License

This project is open source and free to use.
