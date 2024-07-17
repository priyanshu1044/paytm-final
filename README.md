# paytm

## Tech Stack

- **Frontend & Backend**: [Next.js](https://nextjs.org/)
- **Auxiliary Backend**: [Express](https://expressjs.com/)
- **Monorepo Management**: [Turborepo](https://turborepo.org/)
- **Database**: [PostgreSQL](https://www.postgresql.org/)
- **ORM**: [Prisma](https://www.prisma.io/)
- **CSS Framework**: [Tailwind CSS](https://tailwindcss.com/)

## Getting Started

### Prerequisites

Ensure you have the following installed on your machine:

- Node.js (v14 or later)
- PostgreSQL
- pnpm (optional, but recommended for Turborepo for fast dependency installation and caching)

### Installation

1. **Clone the repository:**

   ```sh
   git clone https://github.com/priyanshu1044/paytm-final.git
   ```

2. **Install dependencies:**

   ```sh
   npm install
   ```

3. **Set up the database:**

   - Create a PostgreSQL database.
   - Configure your `.env` file with your database credentials. An example `.env` file might look like:
     ```plaintext
     DATABASE_URL="postgresql://user:password@localhost:5432/database"
     ```

4. **Run database migrations:**
   ```sh
   npx prisma migrate dev --name NAME_OF_MIGRATION
   ```
   ```sh
   npx prisma generate
   ```

### Development

To start the development server, run:

```sh
npm run dev
```
