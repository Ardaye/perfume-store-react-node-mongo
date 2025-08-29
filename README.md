# Perfume Shop

## Overview
The Perfume Shop is an e-commerce application designed to provide users with a seamless shopping experience for perfumes. The application is built using a full-stack approach, utilizing React for the frontend and Node.js with MongoDB for the backend.

## Project Structure
The project is organized into two main directories: `backend` and `frontend`.

### Backend
- **src/**: Contains the source code for the backend application.
  - **controllers/**: Contains the logic for handling requests related to products and reviews.
    - `productController.js`: Handles product-related requests.
    - `reviewController.js`: Handles review-related requests.
  - **models/**: Defines the data models for MongoDB.
    - `product.js`: Defines the Product schema.
    - `review.js`: Defines the Review schema.
  - **routes/**: Contains the API routes for products and reviews.
    - `productRoutes.js`: Routes for product-related API endpoints.
    - `reviewRoutes.js`: Routes for review-related API endpoints.
  - `app.js`: Initializes the Express application and sets up middleware.
  - `db.js`: Establishes a connection to the MongoDB database.
- `package.json`: Contains metadata and dependencies for the backend project.
- `README.md`: Documentation for the backend setup and usage.

### Frontend
- **public/**: Contains static files for the frontend application.
  - `index.html`: The main HTML file for the React application.
- **src/**: Contains the source code for the frontend application.
  - **components/**: Contains reusable components for the application.
    - `Navbar.jsx`: Navigation component.
    - `Banner.jsx`: Call-to-action banner component.
    - `ProductCard.jsx`: Component for displaying individual product information.
    - `ProductGallery.jsx`: Component for displaying multiple images of a product.
    - `Reviews.jsx`: Component for displaying and adding reviews.
    - `ShareButton.jsx`: Component for sharing products on social media.
  - **pages/**: Contains the main pages of the application.
    - `HomePage.jsx`: Homepage layout with navbar, banner, and product cards.
    - `ProductPage.jsx`: Detailed product information, reviews, and image gallery.
  - `App.jsx`: Main component that sets up routing.
  - `index.js`: Entry point for the React application.
  - **styles/**: Contains CSS styles for the frontend application.
    - `main.css`: Styles for the application.
- `package.json`: Contains metadata and dependencies for the frontend project.
- `README.md`: Documentation for the frontend setup and usage.

## Setup Instructions

### Backend
1. Navigate to the `backend` directory.
2. Install dependencies:
   ```
   npm install
   ```
3. Start the server:
   ```
   npm start
   ```
4. Ensure MongoDB is running and connected.

### Frontend
1. Navigate to the `frontend` directory.
2. Install dependencies:
   ```
   npm install
   ```
3. Start the React application:
   ```
   npm start
   ```

## Features
- Responsive design for both desktop and mobile users.
- User-friendly navigation and product browsing experience.
- Ability to view detailed product information and reviews.
- Option to share products on social media platforms.

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue for any suggestions or improvements.

## License
This project is licensed under the MIT License.