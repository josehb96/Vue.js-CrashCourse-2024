# VueJobs - Job Listing Platform with Vue.js

This project is a job listing web application built with Vue.js 3 and Vite. The platform allows users to view, add, edit, and delete jobs, while interacting with a mock server using JSON Server for full CRUD (Create, Read, Update, Delete) functionality. The design is enhanced using Tailwind CSS.

## Features

- **Job Listings:** Display a list of jobs from a JSON file or a mock API.
- **Add Jobs:** Allows users to add new jobs via a form.
- **Edit Jobs:** Facilitates editing job details.
- **Delete Jobs:** Provides the ability to delete jobs.
- **Navigation:** Vue Router is implemented for seamless navigation between views.
- **Notifications:** Toast notifications to indicate successful actions (such as adding or deleting a job).
- **Responsive Design:** Tailwind CSS is used to create a modern, responsive design.
- **Netlify Deployment:** Configured for continuous deployment on Netlify.

## Technologies Used

- **Vue.js 3**
- **Vite**
- **Tailwind CSS**
- **JSON Server**
- **Vue Router**
- **Axios**
- **PrimeIcons**
- **Netlify**

## Installation

Follow the steps below to run this project locally.

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/vuejobs.git
   cd vuejobs
Install the dependencies:

bash
Copiar código
npm install
Start the development server:

bash
Copiar código
npm run dev
In a separate terminal, start the JSON Server:

bash
Copiar código
npm run json-server
Open your browser at http://localhost:3000 to view the application.

Usage
Navigate to the homepage to view the job listings.
Use the "Add Job" button to create a new job.
Click "Edit" to modify an existing job.
Delete a job using the "Delete" button.
Deployment
This project is set up for deployment on Netlify. Every push to the GitHub repository triggers a new automatic deployment on Netlify.

Create a repository on GitHub.
Connect your repository to Netlify.
Configure the production branch in Netlify for continuous deployment.
Available Scripts
npm run dev: Starts the development server.
npm run build: Builds the project for production in the dist folder.
npm run preview: Previews the production build locally.
npm run json-server: Starts the mock JSON server on port 8000.
Contributions
Contributions are welcome! Please follow the standard GitHub workflow to contribute:

Fork the repository.
Create a new branch (git checkout -b feature/new-feature).
Make your changes and commit them (git commit -m 'Add new feature').
Push your changes to your branch (git push origin feature/new-feature).
Open a Pull Request.
