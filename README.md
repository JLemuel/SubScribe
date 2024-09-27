# SubScribe

SubScribe is a simple subscription management system built with Laravel, React, and Inertia.js, featuring Stripe integration for payment processing.

## 🚀 Features

- User authentication (registration, login, password reset)
- Subscription plans (Free, Basic, Premium)
- User dashboard with subscription management
- Stripe integration for secure payments
- Admin panel for user and subscription management

## 🛠 Tech Stack

- Backend: Laravel 11
- Frontend: React 18
- Routing: Inertia.js
- Styling: Tailwind CSS
- Payment Processing: Stripe
- Database: MySQL

## 📋 Prerequisites

- PHP >= 8.3
- Composer
- Node.js >= 20.x
- npm or yarn
- MySQL

## 🚀 Getting Started

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/subscribe.git
   cd subscribe
   ```

2. Install PHP dependencies:
   ```
   composer install
   ```

3. Install JavaScript dependencies:
   ```
   npm install
   ```

4. Copy the .env.example file to .env and configure your environment variables:
   ```
   cp .env.example .env
   ```

5. Generate an application key:
   ```
   php artisan key:generate
   ```

6. Run database migrations:
   ```
   php artisan migrate
   ```

7. Compile assets:
   ```
   npm run dev
   ```

8. Start the development server:
   ```
   php artisan serve
   ```

Visit `http://localhost:8000` in your browser to see the application.

## 🔧 Configuration

1. Set up your database credentials in the `.env` file.
2. Configure Stripe keys in the `.env` file:
   ```
   STRIPE_KEY=your_stripe_publishable_key
   STRIPE_SECRET=your_stripe_secret_key
   ```

## 👥 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).

## 📞 Contact

If you have any questions, feel free to reach out to us at [johnlemuelnicolas@gmail.com](johnlemuelnicolas@gmail.com).
