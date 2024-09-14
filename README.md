Dynamic Recipe App

A dynamic recipe application built with React that allows users to search for recipes, view tutorial videos on YouTube, and manage their favorite recipes. The app features real-time search, API integration for fetching recipes, and a user-friendly interface optimized for both web and mobile devices.

Table of Contents

    Features
    Technologies Used
    Installation
    Usage
    Contributing
    License

Features

    Dynamic Search: Quickly search for recipes using dynamic search functionality.
    API Integration: Fetch recipe details via an API.
    YouTube Integration: Click on a recipe to search for its video tutorial on YouTube.
    Favorites Management: Add recipes to your favorites list and view them anytime.
    Responsive Design: Optimized for both web and mobile devices to ensure a smooth user experience.

Technologies Used

    React.js: Used for building the user interface and managing state.
    Axios: For making HTTP requests to the recipe API.
    Tailwind CSS: For utility-first CSS styling to build custom designs quickly.
    DaisyUI: Provides a set of accessible and customizable UI components that work with Tailwind CSS.
    CSS Modules: For modular and scoped CSS styling.

Installation
Prerequisites

Ensure you have Node.js and npm installed. You can download them from Node.js official site.
Steps

  Clone the Repository:

    bash

    git clone https://github.com/kagan-dev/dynamic-recipe-app.git

Navigate to the Project Directory:

    bash

    cd dynamic-recipe-app

Install Dependencies:

    bash

    npm install

Create a .env File

Add your environment variables in a .env file at the root of the project directory:

  makefile

    REACT_APP_API_URL=your_api_url_here
    REACT_APP_API_KEY=your_youtube_key_here

Start the Application:

    bash

    npm start

    This command will start the development server and open the application in your default web browser. By default, the app will be accessible at http://localhost:3000.

Usage

    Search for Recipes: Use the search bar to find recipes by keyword.
    View Recipe Details: Click on a recipe to see more details and watch a video tutorial on YouTube.
    Manage Favorites: Add recipes to your favorites list and access them from the favorites page.

Contributing

If you'd like to contribute to this project, please follow these steps:

  Fork the Repository and clone it to your local machine.

  Create a new branch for your changes:

    bash

    git checkout -b feature-branch

Make your changes and commit them:

    bash

    git add .
    git commit -m "Add new feature or fix"

Push your changes to your forked repository:

    bash

    git push origin feature-branch

  Open a Pull Request on GitHub.

Some screenshots from application=>

![Ekran görüntüsü 2024-09-15 012934](https://github.com/user-attachments/assets/0adf9cbd-76d7-43c8-99e1-5e39b1caca35)

![Ekran görüntüsü 2024-09-15 013041](https://github.com/user-attachments/assets/d138d166-5880-47b7-8fb2-83700581c1e0)

![Ekran görüntüsü 2024-09-15 013137](https://github.com/user-attachments/assets/321a6ad2-e8a2-4c85-b41c-a6c71960f674)

![Ekran görüntüsü 2024-09-15 012842](https://github.com/user-attachments/assets/7077dd2f-d5fb-4baf-91b6-8b19a4ea9404)

![Ekran görüntüsü 2024-09-15 013230](https://github.com/user-attachments/assets/4f56f7a0-2886-47c0-b6d9-5217942f9fe1)


License

This project is licensed under the MIT License. See the LICENSE file for more details.
