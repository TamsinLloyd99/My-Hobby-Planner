# Hobby Planner

## Overview

The Hobby Planner is a web application designed to help users organize and manage their hobbies and projects in a creative and efficient way. With features like project tracking, deadline visualization, and a customizable scrapbook interface, the Hobby Planner makes it easy for users to stay on top of their personal goals and creative endeavors.

## Features

### 1. Homepage

A welcoming landing page introducing the platform and its features.

**Includes:**
- Navigation bar for seamless navigation.
- Call-to-action buttons such as "Start Planning" or "Explore Projects."
- A featured section showcasing popular or recently updated projects.

### 2. Profile Page

Personalized dashboard displaying user account details.

**Includes:**
- Summary of user activity (e.g., completed projects, upcoming deadlines).
- Editable personal information.

### 3. Project Page

Overview of active and upcoming projects.

**Key Features:**
- Project cards displaying titles, progress, and deadlines.
- Sorting and filtering options for better project management.
- Option to add, edit, or delete projects.

### 4. Calendar Integration

Visualizes deadlines and milestones in an interactive calendar.

**Features:**
- Color-coded statuses for projects (e.g., "In Progress," "Completed").
- Quick-add functionality for tasks directly from the calendar view.
- Milestone reminders.

### 5. Scrapbook Layout

An interactive and customizable interface for personalizing projects.

**Features:**
- Drag-and-drop functionality for photos, notes, and other elements.
- Customization options like stickers, backgrounds, and resizing tools.

### 6. Log-in Page

Secure and user-friendly log-in screen for personalized access.

**Includes:**
- Email/username and password fields.
- "Forgot Password" functionality.
- Third-party login options (e.g., Google or Facebook).

## Tech Stack

### Frontend
- HTML, CSS, JavaScript
- Framework: React 

### Backend
- Node.js with Express (for handling API requests)

### Database
- MongoDB (for storing user profiles, projects, and deadlines)

### Other Tools
- Figma: For designing the user interface.
- GitHub: For version control and collaboration.
- Netlify: For hosting the application.

## Figma Prototype

You can view the Figma design for the Hobby Planner here:  
[[View Figma Prototype](#)](https://www.figma.com/design/ByRcp1vNjl5fygKodXoYM5/My-Hobby-Planner---Main-page?node-id=0-1&t=lt3umpQ8jF7qyW8K-1)

## Installation Instructions

1. **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/hobby-planner.git
    cd hobby-planner
    ```

2. **Install dependencies:**
    ```bash
    npm install
    ```

3. **Set up environment variables:**
    Create a `.env` file in the root directory.  
    Add the following variables:
    ```bash
    MONGO_URI=your_mongodb_connection_string
    PORT=5000
    ```

4. **Start the application:**
    ```bash
    npm start
    ```

5. Access the application at `http://localhost:5000` in your browser.

## Folder Structure

- `/client`: Contains frontend code (React components, pages, and styles).
- `/server`: Backend code including routes, models, and controllers.
- `/figma-design`: Contains exported assets and links to the Figma design.

## Future Enhancements

- **Mobile Responsiveness:** Ensure the app is fully optimized for mobile devices.
- **Notifications:** Add email or in-app notifications for upcoming deadlines and milestones.
- **Social Features:** Allow users to share their projects or collaborate with others.
- **Dark Mode:** Provide a dark mode option for better accessibility and user preference.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements

- Figma for providing an excellent design tool.
- Open-source libraries and frameworks used in this project.

Feel free to fork this repository and customize it to suit your needs. Contributions and suggestions are always welcome!
