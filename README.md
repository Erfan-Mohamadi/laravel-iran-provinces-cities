# Laravel Iran Provinces and Cities

A simple Laravel migration and seeder package for adding Iran's provinces and cities to your project. Perfect for blogs or any Laravel application that requires localized province and city data out of the box.

## Features

- **Comprehensive Data**: Includes a complete list of Iran's provinces and cities.
- **Easy Integration**: Simple migration and seeder setup for quick implementation.
- **Localization Ready**: Ideal for applications targeting Persian-speaking users.

## Installation

To install the package, follow these steps:

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/Erfan-Mohamadi/laravel-iran-provinces-cities.git
   cd laravel-iran-provinces-cities

2. **Copy the Files**:

Copy the database folder into your Laravel project's root directory.

3. **Run the Migrations and Seeders:**:

   ```bash
    php artisan migrate
    php artisan db:seed --class=ProvincesCitiesSeeder

**Usage**:
After running the migrations and seeders, you can access the provinces and cities data in your application. For example:
   ```bash
    use App\Models\Province;
    $provinces = Province::all();
