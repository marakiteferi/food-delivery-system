# JobSpark

JobSpark is a web application built as a group project for a Web Development course. It allows users to create, view, update, and delete job listings, complete with company logos and search functionality.

## Features

- Post, edit, and delete job listings  
- Upload and display company logos  
- Search listings by tags or keywords  
- User registration and login  
- Responsive design with Tailwind CSS

## Prerequisites

- PHP 8.1+  
- Composer  
- MySQL (or other supported database)

## Quick Start

### 1. Clone the repository

```bash
git clone https://github.com/your-username/jobspark.git
cd jobspark
````

### 2. Install dependencies

```bash
composer install
```

### 3. Set up environment

```bash
cp .env.example .env// create a database named "laravel" and set up your credentials 
php artisan key:generate
```

Edit `.env` and fill in your database credentials.

### 4. Migrate and seed database

```bash
php artisan migrate --seed
```

### 5. Link storage

```bash
php artisan storage:link
```

### 6. Serve the app

```bash
php artisan serve
```

Then visit: [http://127.0.0.1:8000](http://127.0.0.1:8000)

---

## Default User Login

You can log in using:

* **Email:** `abebe@gmail.com`
* **Password:** `password`

---

## License

MIT License

---

## Contributors

* @marakiteferi
* @Meti-20
* @thundercode21
* @Kaleb657
* @Lencho123/@Kaneneus(same account)



