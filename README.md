# 🖼️ T3 Gallery

A modern image gallery application built with the T3 stack (Next.js, TypeScript, tRPC, Tailwind CSS).

## 🚀 Features (Planned)

- **Image Management**: Upload, view, and delete images
- **Authentication**: Secure user authentication with Clerk
- **Database**: PostgreSQL database hosted on Vercel
- **Analytics**: User behavior tracking with PostHog
- **Error Monitoring**: Real-time error tracking with Sentry
- **Rate Limiting**: API protection with Upstash
- **Testing**: End-to-end testing with Cypress
- **CI/CD**: Automated deployment with GitHub Actions

## 📋 Development Roadmap

### Core Features
- [ ] Make it deploy
- [ ] Scaffold basic UI with mock data
- [ ] Set up database (Vercel Postgres)
- [ ] Connect database to UI

### Authentication & Security
- [ ] Add authentication (Clerk)
- [ ] Implement rate limiting (Upstash)

### Image Management
- [ ] Add image upload functionality
- [ ] Create routing/image detail pages
- [ ] Implement delete button (server actions)

### Monitoring & Analytics
- [ ] Error management (Sentry)
- [ ] Analytics integration (PostHog)

### Quality Assurance
- [ ] Add end-to-end tests (Cypress)
- [ ] Set up CI/CD pipeline (GitHub Actions)

## 🛠️ Tech Stack

- **Framework**: Next.js 14+ with App Router
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Database**: PostgreSQL (Vercel Postgres)
- **Authentication**: Clerk
- **Error Monitoring**: Sentry
- **Analytics**: PostHog
- **Rate Limiting**: Upstash
- **Testing**: Cypress
- **CI/CD**: GitHub Actions

## 🚀 Getting Started

```bash
# Clone the repository
git clone <repository-url>

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env.local

# Run the development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to see the application.

## 📁 Project Structure

```
t3gallery/
├── src/
│   ├── app/          # Next.js App Router pages
│   ├── components/   # Reusable UI components
│   ├── lib/          # Utility functions and configurations
│   └── server/       # Server-side code (tRPC, database)
├── public/           # Static assets
└── ...
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License.
