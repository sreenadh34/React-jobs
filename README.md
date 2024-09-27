# React-Jobs

A frontend for a job listing application built using React, and Tailwind CSS. This project uses the JSON Server library to mock a REST API as the backend.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Technologies Used](#technologies-used)

## Installation

To set up the project locally, follow these steps:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/React-jobs.git
    cd React-jobs
    ```

2. **Install dependencies:**

    ```bash
    npm install
    ```

3. **Start the JSON Server:**

    ```bash
    npx json-server --watch db.json --port 8000
    ```

4. **Start the development server:**

    ```bash
    npm run dev
    ```

## Usage

After starting the development server, you can view the job listings by navigating to `http://localhost:3000` in your browser. The JSON Server will be running on `http://localhost:8000`, mocking a REST API that serves the job data.

## Features

- View a list of available jobs
- Filter jobs by category, location, or company
- **Create, edit, and delete job listings**
- Responsive design optimized for different screen sizes

## Technologies Used

- **Frontend**: JavaScript, React, Tailwind CSS
- **Mock Backend**: JSON Server

## Build with React + Vite
