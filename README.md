# Web-based Text Editor

This project aims to develop a web-based text editor similar to Microsoft Word, with basic functionalities like text editing, and image insertion. It's built using React on the frontend and Node.js/Express.js on the backend. 

## Features

- User authentication
- Create, read, update, and delete (CRUD) operations for documents
- Rich text editing, including support for bold, italic, underline, and text alignment
- Image insertion and manipulation (drag and drop)

## Tech Stack

**Frontend:** React, Quill.js, Fabric.js

**Backend:** Node.js, Express.js, Passport.js

**Database:** MongoDB

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.

- npm
  ```sh
  npm install npm@latest -g
  ```
- MongoDB
  ```sh
  # Follow the instructions based on your OS at MongoDB's official documentation:
  # https://docs.mongodb.com/manual/administration/install-community/
  ```

### Installation

1. Clone the repository
   ```sh
   git clone https://github.com/your_username_/project_name.git
   ```
2. Install NPM packages for server
   ```sh
   cd server
   npm install
   ```
3. Install NPM packages for client
   ```sh
   cd ../client
   npm install
   ```

## Usage

To start the application:

1. Run MongoDB in a separate terminal
   ```sh
   mongod
   ```
2. Start the server
   ```sh
   cd server
   npm start
   ```
3. Start the client in a new terminal
   ```sh
   cd client
   npm start
   ```
   
Open `http://localhost:3000` to view it in the browser. 

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact
