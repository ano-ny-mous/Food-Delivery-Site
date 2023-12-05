# Food Delivery Site

## Description

Food Delivery Site is a React-based web application that showcases a restaurant listing with search functionality. Users can explore various restaurants, search for specific ones, and view details such as name, cuisine, and average rating.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Components](#components)
- [API Integration](#api-integration)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)

## Installation

To run the Namastha React app locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/ano-ny-mous/Food-Delivery-Site
2. Install dependencies: 
   ```bash
   npm install

## Usage
Run the development server to view the Namastha React app locally:
1. Clone the repository:
   ```bash
   npm start

Visit http://localhost:3000 in your browser to explore the application.

## Components
1. Header
   The Header component displays the logo, navigation items, and a conditional login/logout button.

2. Body
   The Body component handles the main content of the application, including the search bar and a list of restaurant cards.

3. Footer
   The Footer component renders the footer section of the application.

4. RestaurantCard
   The RestaurantCard component represents a card displaying information about a restaurant, such as image, name, cuisines, and average rating.

5. Shimmer
   The Shimmer component is a loading placeholder that is displayed while data is being fetched.

## Technologies Used

Namastha React is built using modern web development technologies and tools. Here's an overview of the key technologies used in the project:

### Frontend

- **React**: A powerful JavaScript library for building user interfaces. React enables the creation of reusable UI components, making it easier to manage complex user interfaces efficiently.

- **React Hooks (useState, useEffect)**: React hooks are used to manage state and side effects in functional components. `useState` is utilized for state management, while `useEffect` is employed for handling side effects like data fetching.

### Styling

- **CSS**: Cascading Style Sheets (CSS) are used for styling the components and ensuring a visually appealing and responsive user interface.

### Build Tool

- **Parcel**: Parcel is a web application bundler that requires zero configuration. It simplifies the build process by automatically handling tasks such as bundling, minification, and hot module replacement.

### API Integration

- **Fetch API**: The Fetch API is used to make asynchronous HTTP requests to the Swiggy API, fetching restaurant data dynamically.

### External Services

- **Cloudinary**: The application leverages Cloudinary as a Content Delivery Network (CDN) for serving restaurant images. The `IMG_CDN_URL` constant in [constants.js](src/constants.js) is set to the base URL for fetching images from Cloudinary.

### Development Environment

- **Node.js and npm**: Node.js is a JavaScript runtime used for server-side scripting, and npm (Node Package Manager) is used for managing project dependencies.

### Version Control

- **Git**: The project uses Git for version control, allowing for collaborative development and tracking changes over time.

### Coding Standards

- **JavaScript ES6+**: The project follows ECMAScript 6 (ES6) standards, taking advantage of modern JavaScript features for cleaner and more maintainable code.

### Testing (if applicable)

- **Jest and React Testing Library**: If testing is implemented, Jest and React Testing Library are common tools for writing and running tests in React applications.

This combination of technologies provides a robust foundation for building scalable and maintainable React applications.

## Contributing
To contribute:

Fork the repository.       
Create a new branch: git checkout -b feature-name.        
Commit your changes: git commit -m 'Add feature'.               
Push to the branch: git push origin feature-name.                 
Submit a pull request.                    
