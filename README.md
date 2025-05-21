# Narayanji Gajak - Distribution Management System

A B2B ordering & operations platform tailored for 300–350+ vendors of Narayanji Gajak across India. This frontend application helps manage orders, pricing, prepayments, warehouse work orders, and live tracking—all from one centralized system.

## Features

- Vendor login system with OTP-based authentication
- Product catalog with vendor-specific pricing
- Cart and order management
- Order review and approval workflow
- Integration with payment gateways
- Live order tracking
- Administrative controls

## Tech Stack

- React with Vite
- Tailwind CSS for styling
- Supabase for authentication
- React Router for navigation

## Getting Started

### Prerequisites

- Node.js (v18+)
- npm or yarn

### Installation

1. Clone the repository
   ```
   git clone https://github.com/your-username/narayanji-frontend.git
   cd narayanji-frontend
   ```

2. Install dependencies
   ```
   npm install
   ```

3. Set up environment variables
   ```
   cp .env.example .env.local
   ```
   Then edit `.env.local` with your actual values.

4. Start the development server
   ```
   npm run dev
   ```

## Project Structure

```
src/
├── assets/                  # Static assets
├── components/              # Reusable UI components
│   ├── auth/                # Authentication components
│   ├── common/              # Shared components
│   ├── layout/              # Layout components
│   └── vendor/              # Vendor-specific components
├── contexts/                # React contexts
├── hooks/                   # Custom hooks
├── pages/                   # Page components
│   ├── auth/                # Login pages
│   └── vendor/              # Vendor pages
├── services/                # API services
│   ├── api.js               # API client
│   └── supabase.js          # Supabase client
├── utils/                   # Utility functions
└── App.jsx                  # Main app component
```

## Branching Strategy

- `feature/sprint1`, `feature/sprint2`, etc. - Feature branches per sprint
- `prod` - Production branch
- `sprint/v1` - Testing branch

## Available Scripts

- `npm run dev` - Start the development server
- `npm run build` - Build for production
- `npm run preview` - Preview the production build locally
- `npm run lint` - Run ESLint

## Contributors

- [Your Name](https://github.com/your-username)
- [Utsav Chindalia](https://github.com/utsav-chindalia)

## License

This project is proprietary and confidential.
