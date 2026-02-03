# Expert Giggle

A modern, type-safe web application built with Bun, Elysia, Zod, Drizzle, and PostgreSQL.

## 🚀 Tech Stack

- **Runtime**: [Bun](https://bun.sh) - Fast all-in-one JavaScript runtime
- **Framework**: [Elysia](https://elysiajs.com) - Fast and friendly Bun web framework
- **Validation**: [Zod](https://zod.dev) - TypeScript-first schema validation
- **ORM**: [Drizzle](https://orm.drizzle.team) - TypeScript ORM with SQL-like query API
- **Database**: [PostgreSQL](https://www.postgresql.org) - Powerful open-source relational database

## 📋 Prerequisites

- **Bun** >= 1.0.0 ([Installation Guide](https://bun.sh/docs/installation))
- **PostgreSQL** >= 14.0 ([Installation Guide](https://www.postgresql.org/download/))

## 🛠️ Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd expert-giggle
```

2. Install dependencies:
```bash
bun install
```

3. Set up environment variables:
```bash
cp .env.example .env
```

4. Configure your `.env` file with your database credentials:
```env
DATABASE_URL=postgresql://user:password@localhost:5432/expert_giggle
PORT=3000
NODE_ENV=development
```

## 🏃 Running the Application

### Development Mode
```bash
bun run dev
```

The server will start on `http://localhost:3000` (or the port specified in your `.env`).

### Production Mode
```bash
bun run build
bun run start
```

## 📦 Available Scripts

- `bun run dev` - Start development server with hot reload
- `bun run build` - Build for production
- `bun run start` - Start production server
- `bun run test` - Run tests

## 🔧 Configuration

### Environment Variables

| Variable | Description | Default |
|----------|-------------|---------|
| `DATABASE_URL` | PostgreSQL connection string | Required |
| `PORT` | Server port | `3000` |
| `NODE_ENV` | Environment mode | `development` |

## 📚 Additional Resources

- [Bun Documentation](https://bun.sh/docs)
- [Elysia Documentation](https://elysiajs.com)
- [Zod Documentation](https://zod.dev)
- [Drizzle Documentation](https://orm.drizzle.team)
- [PostgreSQL Documentation](https://www.postgresql.org/docs/)
