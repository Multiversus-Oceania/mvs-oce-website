# Overview
This is the website for MultiVersus Oceania.

# Installation Instructions

1. Make sure you have PHP and composer installed using your package manager.

```
sudo dnf install php
sudo dnf install composer
sudo dnf install node
```

2. Install other dependencies 

```
sudo dnf install php-pdo
sudo dnf install php-sqlite3
sudo dnf install php-xml
```
3. Check out the repo

```
git clone git@github.com:Multiversus-Oceania/mvs-oce-website.git 
```

4. Install dependencies using composer and set up the project

```
composer update
cp .env.example .env
php artisan key:generate
php artisan migrate
npm i
npm run build
```
5. Run the project

```
php artisan serve
```
