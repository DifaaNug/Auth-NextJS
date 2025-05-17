# Next.js Authentication Project

This is a modern authentication system built with Next.js 15+, featuring a robust and secure authentication implementation using NextAuth.js v5 and Prisma ORM.

## Features

- 🔐 Secure Authentication with NextAuth.js
- 📱 Modern UI with Tailwind CSS
- 🛢️ PostgreSQL Database with Prisma ORM
- 🔒 Password Hashing with bcrypt
- ✅ Form Validation with Zod
- 🚀 Type Safety with TypeScript
- ⚡ Fast Development with Turbopack

## Tech Stack

- **Framework:** [Next.js 15](https://nextjs.org)
- **Authentication:** [NextAuth.js v5](https://next-auth.js.org)
- **Database:** PostgreSQL
- **ORM:** [Prisma](https://prisma.io)
- **Styling:** [Tailwind CSS](https://tailwindcss.com)
- **Icons:** [React Icons](https://react-icons.github.io/react-icons)

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- PostgreSQL database
- npm or yarn or pnpm or bun

### Environment Setup

1. Clone the repository
2. Create a `.env` file in the root directory
3. Add the following environment variables:
   ```env
   DATABASE_URL="postgresql://username:password@localhost:5432/your_db_name"
   AUTH_SECRET="your-auth-secret"
   ```

### Installation

1. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   # or
   bun install
   ```

2. Set up the database:
   ```bash
   npx prisma generate
   npx prisma db push
   ```

3. Run the development server:
   ```bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   # or
   bun dev
   ```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Project Structure

```
├── app/                  # App router directory
│   ├── api/             # API routes
│   ├── auth/            # Authentication related pages
│   └── generated/       # Generated Prisma client
├── prisma/              # Prisma schema and migrations
└── public/              # Static assets
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.

## Acknowledgments

- [Next.js Documentation](https://nextjs.org/docs)
- [NextAuth.js Documentation](https://next-auth.js.org)
- [Prisma Documentation](https://www.prisma.io/docs)
