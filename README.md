# Duality Game

A modern 3D adventure game built with Next.js 14, featuring dynamic character paths and immersive gameplay.

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Project Structure

```
duality-game/
├── src/
│   ├── app/              # Next.js 14 App Router
│   ├── components/       # React components
│   ├── lib/             # Utility functions
│   └── styles/          # Global styles
├── public/              # Static assets
└── package.json         # Dependencies
```

## Features

- ⚡️ Next.js 14 with App Router
- 🎮 Three.js for 3D graphics
- 🎨 Tailwind CSS for styling
- 🔒 TypeScript for type safety
- 🗄️ PostgreSQL for database
- 🔄 Redis for caching
- 💳 Stripe for payments

## Learn More

To learn more about the technologies used in this project:

- [Next.js Documentation](https://nextjs.org/docs)
- [Three.js Documentation](https://threejs.org/docs)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [TypeScript Documentation](https://www.typescriptlang.org/docs/)

## Development

```bash
# Install dependencies
npm install

# Run development server
npm run dev

# Build for production
npm run build

# Start production server
npm start

# Run linter
npm run lint
```

## Environment Variables

Create a `.env.local` file in the root directory:

```env
DATABASE_URL=your_postgres_url
REDIS_URL=your_redis_url
STRIPE_SECRET_KEY=your_stripe_key
NEXT_PUBLIC_API_URL=http://localhost:3000
```

## Deployment

The easiest way to deploy is using the [Vercel Platform](https://vercel.com/new).

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fyourusername%2Fduality-game)

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
