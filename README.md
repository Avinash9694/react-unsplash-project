# React Unsplash Project

Welcome to the React Unsplash Project! This React application leverages the Unsplash API to search and display a collection of images. Users can scroll through the images and load more as they reach the bottom of the page.

## Live Demo

Explore the live demo: [React Unsplash Project](https://react-unsplash1.netlify.app/)

## Overview

The project uses React and the Unsplash API to fetch and display images based on user search queries. It implements infinite scrolling, allowing users to load more images as they reach the end of the page. The UI components include a search bar, photo display, and user information.

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/Avinash9694/react-unsplash-project.git
   cd react-unsplash-project
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Obtain Unsplash API Key:

   - Create a developer account on Unsplash (https://unsplash.com/developers).
   - Create a new application to get the API key.

4. Create a `.env` file in the project root directory and add your Unsplash API key:

   ```
   REACT_APP_ACCESS_KEY=your_api_key_here
   ```

5. Run the project:

   ```bash
   npm start
   ```

Visit [http://localhost:3000](http://localhost:3000) in your browser to explore the React Unsplash Project.

## Features

- **Image Search:** Enter search queries to fetch and display relevant images.
- **Infinite Scrolling:** Load more images as you reach the bottom of the page.

## Components

- **App.js:** Main React component handling image fetching, search, and infinite scrolling.
- **Photo.js:** Component for rendering individual photos with user information.

## API Integration

The project integrates with the Unsplash API to fetch and display images. The API key is required for authentication.
