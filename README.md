# rilt-stack

A project using React, Inertia.js, Laravel, and Tailwind CSS.

## Table of Contents

- [rilt-stack](#rilt-stack)
  - [Table of Contents](#table-of-contents)
  - [Installation](#installation)
    - [Prerequisites](#prerequisites)
    - [Steps](#steps)
  - [Screenshot](#screenshot)
  - [Contributing](#contributing)
  - [License](#license)

## Installation

### Prerequisites

Make sure you have the following installed on your machine:

- [Node.js](https://nodejs.org/)
- [Composer](https://getcomposer.org/)
- [PHP](https://www.php.net/)
- [Laravel](https://laravel.com/docs/installation)

### Steps

1. **Clone the repository:**

   ```sh
   git clone https://github.com/codeirawan/rilt-stack.git
   cd rilt-stack
   ```
2. **Install dependencies:**

   ```sh
   composer install
   npm install
   ```
3. **Set up environment variables:**

   Copy the `.env.example` file to `.env` and fill in your database and other configurations.

   ```sh
   cp .env.example .env
   php artisan key:generate
   ```
4. **Migrate the database:**

   ```sh
   php artisan migrate --seed
   ```

   This will also run the seeders to populate your database with initial data, including a user account with the following credentials:

   - **Email:** codeirawan@gmail.com
   - **Password:** password
5. **Build front-end assets:**

   ```sh
   npm run dev
   ```
6. **Run the application:**

   ```sh
   php artisan serve
   ```

   Your application should now be running on [http://localhost:8000](http://localhost:8000).

## Screenshot

![1721010556107](image/README/1721010556107.png)
![1721010724972](image/README/1721010724972.png)

## Contributing

If you would like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature/your-feature-name`).
6. Open a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

```

```
