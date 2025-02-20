# E-commerce-website 
# E-commerce Store with React, Supabase, and Paytm

A modern e-commerce platform built with React, TypeScript, Tailwind CSS, and Supabase for the backend. Features include user authentication, shopping cart management, wishlists, and Paytm payment integration.

## Features

- 🛍️ Product browsing and searching
- 🛒 Shopping cart management
- 👤 User authentication (signup/login)
- 💳 Paytm payment integration
- 🌓 Dark/Light mode toggle
- 📱 Responsive design
- 🔒 Secure user data handling with Supabase

## Prerequisites

Before you begin, ensure you have the following installed:
- [Node.js](https://nodejs.org/) (version 18 or higher)
- [npm](https://www.npmjs.com/) (usually comes with Node.js)

## Getting Started

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <project-directory>
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file in the root directory with your Supabase credentials:
   ```env
   VITE_SUPABASE_URL=your_supabase_url
   VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

5. Open your browser and navigate to `http://localhost:5173`

## Project Structure

```
├── src/
│   ├── components/     # React components
│   ├── context/       # React context providers
│   ├── lib/           # Utility functions and API clients
│   ├── types/         # TypeScript type definitions
│   ├── App.tsx        # Main application component
│   └── main.tsx       # Application entry point
├── public/            # Static assets
└── supabase/          # Supabase migrations and configurations
```

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build locally
- `npm run lint` - Run ESLint for code quality

## Database Setup

The application uses Supabase as its backend. The database schema includes:

- Users and Profiles
- Products
- Orders and Order Items
- Wishlists
- Payment Methods

## Authentication

The application uses Supabase Authentication with email/password login. Users can:

1. Sign up with email and password
2. Sign in to existing accounts
3. Sign out
4. Update their profile information

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Support

For support, please open an issue in the repository or contact the maintainers.
