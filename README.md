# ZNain-Builders

ZNain-Builders is a comprehensive full-stack application designed for a leading real estate agency. It allows users to buy, sell, and rent properties seamlessly while providing administrators with tools to manage listings, clients, and transactions efficiently.

## Features

### User Features
- **Property Listings**: View detailed listings of properties available for sale, rent, or purchase.
- **Search & Filters**: Find properties based on location, price range, property type, and more.
- **User Accounts**: Sign up, log in, and manage your profile.
- **Favorites**: Save properties to your favorites for quick access.
- **Contact Agents**: Reach out directly to agents for inquiries.

### Admin Features
- **Property Management**: Add, edit, or remove property listings.
- **User Management**: Manage user accounts and permissions.
- **Transaction Insights**: View and manage buying/selling transactions.

## Tech Stack

### Frontend
- **React**: For building a dynamic and responsive user interface.
- **Tailwind CSS**: For efficient and customizable styling.

### Backend
- **Node.js**: For handling server-side logic.
- **Express.js**: For building RESTful APIs.

### Database
- **MongoDB**: For storing property listings, user data, and transactions.

### Other Tools
- **JWT Authentication**: For secure user login and session management.
- **Cloudinary**: For image hosting and management (property photos).
- **Mongoose**: For database modeling and interaction.

## Installation

### Prerequisites
Ensure you have the following installed:
- Node.js
- MongoDB

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/znain-builders.git
   ```
2. Navigate to the project folder:
   ```bash
   cd znain-builders
   ```
3. Install dependencies for the frontend and backend:
   ```bash
   cd client
   npm install
   cd ../server
   npm install
   ```
4. Set up environment variables:
   Create a `.env` file in the `server` folder and add the following:
   ```env
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret_key
   ```
5. Start the development servers:
   - Backend:
     ```bash
     cd server
     npm start
     ```
   - Frontend:
     ```bash
     cd client
     npm start
     ```
6. Open your browser and navigate to `http://localhost:3000` to view the application.

## Folder Structure
```
znain-builders/
|-- client/          # Frontend React application
|-- server/          # Backend Node.js application
|-- README.md        # Project documentation
```

## Contributing
We welcome contributions to improve ZNain-Builders! Please follow these steps:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m 'Add feature-name'
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

## License
This project is licensed under the [MIT License](LICENSE).

## Contact
For any inquiries, feel free to contact us:
- Email: julkar10121@gmail.com
- Phone: +8801780055645

---

Thank you for using ZNain-Builders! We hope it helps you achieve your real estate goals.
