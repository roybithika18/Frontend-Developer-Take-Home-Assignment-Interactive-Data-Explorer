# Frontend-Developer-Take-Home-Assignment-Interactive-Data-Explorer
Overview

This is a React.js web application called Product Showcase Explorer. It allows users to browse, filter, sort, and view details of products fetched from the DummyJSON Products API
. The app is responsive, user-friendly, and includes animations for enhanced user experience.

Features

Fetch & Display Products: Products are fetched from the API and displayed in a responsive grid layout.

Filtering: Users can filter products by category.

Sorting: Sort products by price (ascending/descending) or title (A-Z/Z-A).

Product Detail View: Click on a product to view detailed information (description, rating, stock, brand, category, multiple images).

Loading & Error Handling: Shows spinners during loading and user-friendly error messages if API calls fail.

Responsive Design: Works on mobile, tablet, and desktop screens.

Animations (Bonus 1):

Product cards fade/slide in with staggered animation

Smooth transition for product detail view

Subtle hover effects and micro-interactions

Tech Stack

Frontend: React.js

Styling: Bootstrap, CSS

API Calls: Axios

Animations: Framer Motion

How to Run Locally

Clone the repository

git clone <your-github-repo-link>
cd interactive-data-explorer


Install dependencies

npm install


Start the development server

npm start


Open your browser
Visit http://localhost:3000

Deployment

The app is deployed and accessible here:
[Your Vercel/Netlify link]

Design Choices

Bootstrap: Used for quick responsive layout and buttons.

Framer Motion: Smooth animations enhance UX without affecting performance.

Axios: Simplifies API calls and error handling.

State Management: React useState and useEffect hooks used for simplicity.

Bonus

Completed Bonus 1: Advanced Animations.

Cards animate on load, details open with smooth transition, and hover interactions are animated.

Libraries Used

axios: API requests

bootstrap: Layout and UI

framer-motion: Animations
