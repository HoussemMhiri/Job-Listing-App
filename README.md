# Job Listing Website

This project is a job listing website built with Laravel and Tailwind CSS. It allows users to manage job listings and provides features like filtering by tags, searching for job, and secure authentication and authorization.

## Features

- **Manage Listings:**
  - Add new job listings.
  - Edit existing job listings.
  - Delete job listings.

- **Search & Filter:**
  - Search for jobs.
  - Filter job listings by tags.

- **Authentication & Authorization:**
  - Secure user authentication.
  - Authorization to control access to job management features.

## Tech Stack

- **Laravel:** Backend framework for building the application.
- **Tailwind CSS:** Utility-first CSS framework for styling.
- **MySQL:** Database management.

## Installation

### Prerequisites

- PHP >= 7.4
- Composer
- MySQL
- Node.js & npm

### Setup

1. **Clone the repository:**

    ```bash
    git clone https://github.com/HoussemMhiri/Job-Listing-App.git
    ```

2. **Install PHP dependencies:**

    ```bash
    composer install
    ```

3. **Install Node.js dependencies:**

    ```bash
    npm install
    ```

4. **Set up environment variables:**

    - Copy `.env.example` to `.env`.
    - Configure your database settings in the `.env` file.

    ```env
    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=your_database
    DB_USERNAME=your_username
    DB_PASSWORD=your_password
    ```

5. **Generate the application key:**

    ```bash
    php artisan key:generate
    ```

6. **Run database migrations:**

    ```bash
    php artisan migrate
    ```

7. **Run the development server:**

    ```bash
    php artisan serve
    ```

8. **Compile assets:**

    ```bash
    npm run dev
    ```

9. **Access the app:** Open your browser and go to `http://localhost:8000`.

## Usage

- **Job Management:** Add, edit, and delete job listings through an intuitive interface.
- **Search & Filter:** Easily find jobs by name or filter listings by tags.
- **Authentication:** Log in to manage job listings with secure access.

## Contributing

Contributions are welcome! Please submit a pull request or open an issue to discuss any ideas.
 
### Contact
For any inquiries, feel free to reach out to me at houssemmhiri95@gmail.com.
