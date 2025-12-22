# 🪨 Sugar Stone

A modern, production-ready web application built with **Next.js 14**, **TypeScript**, and **Tailwind CSS**.

## 🚀 Features

- ⚡ **Next.js 14** with App Router for optimal performance
- 🔒 **TypeScript** for type safety and better developer experience
- 🎨 **Tailwind CSS** for modern, responsive styling
- ✅ **ESLint** configured for code quality
- 🔄 **CI/CD Pipeline** with automated testing and building
- 📱 **Responsive Design** works on all devices
- 🌙 **Dark Mode** support built-in
- 🔐 **Security Headers** configured out of the box

## 📋 Prerequisites

Before you begin, ensure you have the following installed:

- **Node.js** 18.x or higher
- **npm** or **yarn** package manager
- **Git** for version control

## 🛠️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/werner073-sys/sugar-stone.git
cd sugar-stone
```

### 2. Install dependencies

```bash
npm install
```

### 3. Run the development server

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to see the application.

## 📦 Available Scripts

- `npm run dev` - Start development server on http://localhost:3000
- `npm run build` - Create production build
- `npm start` - Start production server
- `npm run lint` - Run ESLint to check code quality
- `npm run type-check` - Run TypeScript type checking

## 🏗️ Project Structure

```
sugar-stone/
├── .github/
│   └── workflows/
│       └── blank.yml          # CI/CD pipeline configuration
├── public/                     # Static files
│   └── favicon.ico
├── src/
│   ├── app/                   # Next.js App Router
│   │   ├── api/               # API routes
│   │   │   └── hello/
│   │   │       └── route.ts   # Example API endpoint
│   │   ├── layout.tsx         # Root layout
│   │   ├── page.tsx           # Home page
│   │   └── globals.css        # Global styles
│   ├── components/            # Reusable React components
│   │   └── Header.tsx         # Navigation header
│   ├── lib/                   # Utility functions
│   │   └── utils.ts
│   └── types/                 # TypeScript type definitions
│       └── index.ts
├── .eslintrc.json            # ESLint configuration
├── .gitignore                # Git ignore rules
├── next.config.js            # Next.js configuration
├── package.json              # Dependencies and scripts
├── postcss.config.js         # PostCSS configuration
├── tailwind.config.ts        # Tailwind CSS configuration
└── tsconfig.json             # TypeScript configuration
```

## 🔧 Configuration

### Environment Variables

Create a `.env.local` file in the root directory for local environment variables:

```env
# Example environment variables
NEXT_PUBLIC_API_URL=http://localhost:3000/api
```

### TypeScript

The project uses strict TypeScript configuration. Path aliases are configured:

- `@/components` → `src/components`
- `@/lib` → `src/lib`
- `@/types` → `src/types`

### Tailwind CSS

Tailwind is configured with:
- Dark mode support (class-based)
- Custom color scheme
- Responsive breakpoints

## 🚀 Deployment

### Vercel (Recommended)

The easiest way to deploy is using [Vercel](https://vercel.com):

```bash
npm install -g vercel
vercel
```

### Other Platforms

You can deploy to any platform that supports Node.js:

1. Build the application: `npm run build`
2. Start the production server: `npm start`

## 🧪 Testing

The CI/CD pipeline automatically runs:

- ✅ ESLint checks
- ✅ TypeScript type checking
- ✅ Production build verification
- ✅ Tests (when available)

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m 'Add amazing feature'`
4. Push to the branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Built with [Next.js](https://nextjs.org/)
- Styled with [Tailwind CSS](https://tailwindcss.com/)
- Type safety by [TypeScript](https://www.typescriptlang.org/)

---

Made with ❤️ by [werner073-sys](https://github.com/werner073-sys)