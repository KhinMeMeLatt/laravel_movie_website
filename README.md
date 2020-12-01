## Movies Website

This website is created by using laravel, tailwind css, livewire and alpine.js. 

## Installation

### Prerequisites
-   To run this project, you must have PHP 7 and above installed.

### Step 1
Begin by cloning this repository to your machine, and installing all Composer & NPM dependencies using the following commands.

```bash
git clone git@github.com:KhinMeMeLatt/laravel_movie_website.git
cd laravel_movie_website && composer install && npm install
php artisan key:generate
npm run dev
```

### Movies database
-   TMDb API is used to pull movie information. Set your TMDB_TOKEN in your `.env` file as below. 
```properties
TMDB_TOKEN = YOUR_TMDB_TOKEN
```
If you don't have api, get it from [TMDB](https://www.themoviedb.org/)

### Step 2
Run the application using the following command.

```bash
php artisan serve
```

## Acknowledgement
-   **Andre Madarang** - [Laravel Movie App](https://www.youtube.com/watch?v=9OKbmMqsREc)