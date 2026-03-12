# Acme Dashboard

A modern, full-featured dashboard application built with Next.js 16 and React. This project demonstrates best practices in server-side rendering, client-side components, and database integration.

## Project Description

Acme Dashboard is a comprehensive administrative interface for managing customers and invoices. It showcases Next.js App Router capabilities, Tailwind CSS styling, and PostgreSQL database integration with dynamic data fetching and real-time search filtering.

## Current Stage

**In Development** - Core features implemented with ongoing enhancements. The dashboard includes:
- ✅ Customer management interface
- ✅ Invoice CRUD operations
- ✅ Dashboard analytics cards and charts
- ✅ Search and pagination functionality
- ✅ Database seeding and setup
- 🔄 Additional features and optimizations in progress

## Features

- **Dashboard Overview**: Real-time statistics and revenue charts
- **Customer Management**: View and manage customer information with search capabilities
- **Invoice Management**: Create, edit, view, and delete invoices with filtering
- **Navigation**: Responsive sidebar with active route highlighting
- **Database Integration**: PostgreSQL with seed data for development
- **Server Components**: Optimized performance using Next.js Server Components
- **Client Components**: Interactive features with React hooks
- **Responsive Design**: Mobile-friendly interface with Tailwind CSS
- **Type Safety**: Full TypeScript support throughout the application

## Setup Instructions

### Prerequisites
- Node.js 18+ 
- pnpm (or npm/yarn)
- PostgreSQL database

### Installation

1. **Clone the repository**
   ```bash
   cd nextjs-dashboard
   ```

2. **Install dependencies**
   ```bash
   pnpm install
   ```

3. **Set up environment variables**
   Create a `.env.local` file in the root directory with your database credentials:
   ```
   POSTGRES_URL="your_database_connection_string"
   ```

4. **Setup the database**
   ```bash
   pnpm run seed
   ```
   This populates the database with sample customers and invoices.

5. **Run the development server**
   ```bash
   pnpm dev
   ```
   Open [http://localhost:3000](http://localhost:3000) in your browser.

### Available Scripts

- `pnpm dev` - Start development server with Turbopack
- `pnpm build` - Build for production
- `pnpm start` - Start production server
- `pnpm seed` - Seed the database with sample data

## Project Structure

```
app/
├── dashboard/          # Dashboard routes
│   ├── customers/      # Customer management page
│   ├── invoices/       # Invoice management page
│   └── layout.tsx      # Dashboard layout
├── ui/                 # Reusable UI components
│   ├── dashboard/      # Dashboard-specific components
│   ├── invoices/       # Invoice-specific components
│   └── forms/          # Form components
├── lib/                # Utility functions and data fetching
└── seed/               # Database seeding script

public/                 # Static assets
```

## Technology Stack

- **Framework**: Next.js 16.0.10
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Database**: PostgreSQL
- **Icons**: Heroicons
- **Build Tool**: Turbopack
- **Package Manager**: pnpm

## Learning Resources

This project is based on the [Next.js App Router Course](https://nextjs.org/learn) on the Next.js Website. For more information and detailed tutorials, visit the course curriculum.

## License

This project is created for educational purposes as part of the Web Design & Development program (WDD430).
