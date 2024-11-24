# PayKings Site

A comprehensive payment processing solutions platform built with Next.js and Sanity CMS, offering specialized payment solutions across multiple industries.

## Overview

PayKings is a modern web platform that provides payment processing solutions tailored to various industries. The platform features industry-specific solutions, developer resources, and comprehensive documentation for integration.

## Tech Stack

- **Frontend Framework:** Next.js 13+ with App Router
- **Content Management:** Sanity CMS
- **Styling:** Tailwind CSS
- **Package Manager:** pnpm
- **Form Handling:** Custom form components with validation
- **API Integration:** REST APIs for leads, search, and notifications
- **SEO:** Built-in sitemap generation and meta optimization

## Features

- 🏢 Industry-specific payment solutions
- 💻 Developer documentation and resources
- 📱 Responsive design for all devices
- 🔍 Integrated search functionality
- 📝 Blog system with author management
- 📊 Lead generation forms
- 📧 Email subscription system
- 🔄 Real-time content updates via Sanity

## Getting Started

1. **Clone the repository**

```bash
git clone [repository-url]
cd paykings-site
```

2. **Install dependencies**

```bash
pnpm install
```

3. **Set up environment variables**

Create a `.env.local` file in the root directory and add necessary environment variables (contact team for required values).

4. **Run the development server**

```bash
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) to view the site.

## Project Structure

```
├── app/                  # Next.js app directory
│   ├── (default)/       # Default layout routes
│   ├── (minimal)/       # Minimal layout routes
│   └── api/             # API routes
├── components/          # React components
│   ├── blog/           # Blog-related components
│   ├── content/        # Content sections
│   ├── forms/          # Form components
│   └── ui/             # UI components
├── lib/                # Utility functions and configs
├── public/             # Static assets
└── sanity/            # Sanity CMS configuration
```

## Development Guidelines

- Follow the existing code structure and naming conventions
- Use Tailwind CSS for styling
- Implement responsive designs for all components
- Add proper TypeScript types for all new features
- Keep components modular and reusable
- Use the provided form validation utilities for new forms

## Deployment

The site is configured for deployment on Vercel. The production branch is automatically deployed to the live site.

```bash
# Build for production
pnpm build

# Preview production build
pnpm start
```

## Additional Resources

- [Next.js Documentation](https://nextjs.org/docs)
- [Sanity CMS Documentation](https://www.sanity.io/docs)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
