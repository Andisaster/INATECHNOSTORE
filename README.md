INASTORE: Book Sales Website with Laravel

INASTORE is a web-based e-commerce platform for online book sales built with Laravel. With INASTORE, users can easily buy books, and admins can manage book collections, transactions, and users.

Key Features:
- Book Management: Add, edit, and delete books with details such as title, author, price, and stock.
- Payment System: Users can purchase books with various payment methods.
- User Authentication: Login and register users with the secure Laravel Auth system.
- Reading Books: Users can read what they have purchased on my book page.

Technologies Used:
- Backend: Laravel (PHP Framework)
- Frontend: Blade Templating, Bootstrap (CSS Framework)
- Database: MySQL

Installation:
1. Clone Repository:
git clone https://github.com/Andisaster/INATECHNOSTORE.git

2. Install Dependencies:
Move to the project directory and install dependencies using Composer:
cd inastore
composer install

3. Environment Configuration:
Copy the .env.example file to .env and adjust the database configuration:
cp .env.example .env
php artisan key:generate

4. Database Migration:
Run migrations to create tables in the database:
php artisan migrate

5. Run the Application:
Run the application using Artisan server:
php artisan serve
Access the application at http://localhost:8000

Contribution:
If you are interested in contributing, please fork the repository this and create a pull request with your changes. Be sure to follow the contribution guidelines and write a clear description of the changes.
