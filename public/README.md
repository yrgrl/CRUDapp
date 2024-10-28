# TechgetAfrica Shop - CRUD Application

A simple CRUD (Create, Read, Update, Delete) web application for managing items in the TechgetAfrica Shop.

## Features

- Add new items to the shop
- View all items in a list
- Delete items from the shop
- Clean and responsive user interface

## Tech Stack

- Backend: Node.js with Express.js
- Frontend: HTML, CSS, and Vanilla JavaScript
- Data Storage: In-memory array (non-persistent)


## Setup and Running

1. Ensure you have Node.js installed on your system.

2. Clone the repository:
https://github.com/yrgrl/CRUDapp.git
3. Install dependencies.

4. Start the server.

5. Open a web browser and navigate to `http://localhost:3000`

## API Endpoints

- GET `/items` - Retrieve all items
- POST `/items` - Create a new item
- GET `/items/:id` - Retrieve a specific item
- PUT `/items/:id` - Update a specific item
- DELETE `/items/:id` - Delete a specific item

## Future Improvements

- Implement persistent storage (e.g., database)
- Add update functionality to the frontend
- Implement user authentication
- Add categories for items

## Contributing

Contributions, issues, and feature requests are welcome. Feel free to check issues page if you want to contribute.

## License

[MIT](https://choosealicense.com/licenses/mit/)