# Serverless Laravel Template for SAM (Default)

## Technologies

- **[Laravel 8.x](https://github.com/laravel/framework/tree/8.x) Framefork**
- **[bref](https://github.com/brefphp/bref) PHP Runtime + Composer Package**

## Setup

### 1. Clone this repository
```
git clone https://github.com/laravel-expansions/serverless-laravel-template-sam-default.git
```

### 2. Install composer packages (bref/bref and bref/laravel-bridge pre installed)
```
composer insttall
```

### 3. Create .env
```
cp .env.example .env && php artisan key:generate
```

## Deploy

Run SAM CLI commands
```
sam build && sam deploy --guided
```
