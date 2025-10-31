# 🚀 Keteraf VILT Starter Kit

An enriched laravel starter kit based on the VILT stack (Vue, Inertia, Laravel, Tailwind CSS).

## ✨ Features

- **Laravel 12** - The latest version of the popular PHP framework
- **Vue 3** - The progressive JavaScript framework with Composition API
- **Inertia.js** - The modern approach to building server-driven single-page apps
- **Tailwind CSS 4** - Utility-first CSS framework for rapid UI development
- **Pest PHP** - An elegant PHP testing framework with a focus on simplicity
- **Pint** - An opinionated PHP code style fixer for Laravel
- **PHPStan** - PHP Static Analysis Tool for finding errors in your code
- **Laravel MCP** - A simple and elegant way for AI clients to interact with your Laravel application
- **Rector** - Instant upgrades and automated refactoring of your PHP code
- **ESLint & Prettier** - Keep your code clean and consistent

## 🚦 Requirements

- PHP 8.4 or higher
- Composer
- Node.js (v18+) and npm

## 🛠️ Installation

```bash
# Create a new Laravel application using this starter kit
laravel new my-app --using=keteraf/vilt-starter-kit

# Navigate to the project directory
cd my-app
```

All dependencies will be automatically installed and assets will be built during the installation process.

## 🏃‍♂️ Development

```bash
# Start the development server with hot-reloading
composer dev

# Or with SSR (Server-Side Rendering)
composer dev:ssr
```

## 🧪 Testing

```bash
# Run all tests
composer test

# Run specific test types
composer test:refactor  # Check code refactoring
composer test:lint      # Check code style
composer test:types     # Check PHP types
composer test:unit      # Run unit tests

# Frontend tests
npm run test:lint       # Check frontend code style
npm run test:types      # Check TypeScript types
```

## 🧹 Code Quality

```bash
# Fix PHP code style
composer lint

# Refactor PHP code
composer refactor

# Fix JavaScript/Vue code style
npm run lint
```

## 📦 Building for Production

```bash
# Build frontend assets
npm run build

# Or with SSR
npm run build:ssr
```

## 🏗️ Project Structure

The starter kit follows the standard Laravel project structure with some additional conventions:

- `app/Actions` - For business logic using the Actions pattern
- `app/Http/Controllers` - For handling HTTP requests
- `app/Http/Requests` - For form validation using FormRequest
- `app/Models` - For database models
- `resources/js` - For Vue components and frontend code
- `tests` - For Pest PHP tests

## 📝 Coding Standards

This starter kit enforces strict coding standards:

- PHP 8.4+ features
- Strict types and array shapes via PHPStan
- Pint for PHP code style
- ESLint and Prettier for JavaScript/Vue code style

## 📄 License

This starter kit is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
