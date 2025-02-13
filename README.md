# Full Stack MERN AI Image Generation App (MidJourney & DALL-E Clone)

This project is a full-stack web application built with the MERN (MongoDB, Express.js, React, Node.js) stack and integrates with OpenAI's DALL-E model for AI-powered image generation. It allows users to generate images based on text prompts, save the generated images, and view them on the homepage.

The application also uses Cloudinary for image storage and management.

## Features

- **User Input**: Enter text prompts to generate images using DALL-E.
- **Image Display**: View generated images on the homepage.
- **Image Storage**: Save generated images in a database and upload them to Cloudinary.
- **Full-stack**: MERN stack for the backend (Node.js, Express, MongoDB) and frontend (React).

## Technologies Used

- **Frontend**:
  - React.js
  - TailwindCSS for styling
  - Axios for making API requests
- **Backend**:
  - Node.js
  - Express.js
  - MongoDB for data storage
  - Cloudinary for image hosting
  - OpenAI's API for image generation (DALL-E)
- **Deployment**:
  - Deployed on Render (for both frontend and backend)

## Features Walkthrough

### Home Page:
- The homepage allows users to input a prompt and generate images using DALL-E.
- The generated images are displayed on the homepage after the API request.

### Create Post:
- After generating an image, users can save the image along with their prompt to the database. This feature utilizes Cloudinary for image storage.

### View Posts:
- All saved posts (prompts and images) are displayed on the homepage. Users can view the image associated with each prompt.
