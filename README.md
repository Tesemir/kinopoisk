# Kinopoisk Lite 
The parody to Kinopoisk where users can browse, leave reviews and search movies.

## Features
- Browse and search movies
- Leave reviews and ratings
- Secure database using PDO
- PHPMyAdmin for easy managing the database

## Technologies
- PHP 8.2
- PDO for database connection
- Lando for containerization
- Composer
- PHPMyAdmin

## Quick start
1. Clone the repository
```text
git clone https://github.com/Tesemir/kinopoisk.git
cd kinopoisk
composer install
```
2. Start Lando
```text
lando start
```
3. Import database

## Database Structure
The database has 4 tables:
- categories
  - Columns: id, name, created_at, updated_at.
- movies
  - Columns: id, category_id (foreign key), name, description, preview, created_at, updated_at.
- reviews
  - Columns: id, user_id, movie_id, review, rating, created_at, updated_at.
- users
  - Columns: id, name, email, password, is_admin, created_at, updated_at.

## Screenshots
![image](https://github.com/user-attachments/assets/c733503a-452b-4c40-a378-786c8c27cc46)
![image](https://github.com/user-attachments/assets/f31c0b92-f298-4110-8984-dbc848759fe7)
![image](https://github.com/user-attachments/assets/cd40a9be-b00d-498d-aef5-9ad468c61d57)
![image](https://github.com/user-attachments/assets/679cc95e-fd8e-492f-9b04-e4619c65cc5e)
![image](https://github.com/user-attachments/assets/d0e8bf7d-17f0-4723-84b0-8f79cefc4b2c)



