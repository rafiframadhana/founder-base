# Founder Base

A fullstack web application built with Next.js and Sanity CMS for connecting founders and showcasing startups.

![FounderBase Screenshot](https://i.imgur.com/msTZIxx.png)

## Tech Stack

- **Frontend**: Next.js 15 with App Router
- **Styling**: Tailwind CSS
- **CMS**: Sanity.io
- **Authentication**: NextAuth.js
- **UI Components**: Custom components with shadcn/ui
- **TypeScript**: For type safety and better developer experience

## Features

- 🔒 User authentication and authorization
- 👥 User profiles
- 🚀 Startup profiles with detailed information
- 🔍 Search functionality for startups
- ✨ Modern and responsive UI
- 📝 Content management through Sanity Studio
- 🎨 Custom font integration (Work Sans)

## Project Structure

```
app/                  # Next.js app directory
├── (root)/           # Main application routes
├── api/              # API routes
└── studio/          # Sanity Studio integration

components/           # React components
├── ui/              # Reusable UI components
└── ...              # Feature-specific components

lib/                  # Utility functions and shared logic
sanity/              # Sanity CMS configuration and schemas
```

## Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up environment variables:
   - Create a `.env.local` file
   - Add necessary environment variables for Next.js and Sanity

4. Run the development server:
   ```bash
   npm run dev
   ```

The application will be available at `http://localhost:3000`

## Sanity Studio

Access the Sanity Studio at `http://localhost:3000/studio` to manage content.

## Features

### User Features
- Create and manage user profiles
- View other users' profiles
- Authentication with NextAuth.js

### Startup Features
- Create startup profiles
- View startup details
- Search and filter startups
- Update startup information


## License

This project is licensed under the MIT License.