# 🎓 Converso - AI-Powered Learning Companion Platform

A modern SaaS learning platform that enables personalized education through AI-powered voice companions. Built with Next.js, TypeScript, and cutting-edge AI technologies, Converso transforms traditional learning into engaging voice-based conversations.

[![Next.js](https://img.shields.io/badge/Next.js-14-black?style=flat-square&logo=next.js)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue?style=flat-square&logo=typescript)](https://www.typescriptlang.org/)
[![Supabase](https://img.shields.io/badge/Supabase-Database-green?style=flat-square&logo=supabase)](https://supabase.com/)
[![Vercel](https://img.shields.io/badge/Deployed%20on-Vercel-black?style=flat-square&logo=vercel)](https://vercel.com/)

## 🌐 Live Demo

**[View Live Application →](https://saas-app-sandy-five.vercel.app/)**

## 🌟 Features

### 🤖 AI Learning Companions
- **Personalized Learning**: Create custom AI companions tailored to specific subjects (Math, Coding, Science, etc.)
- **Voice-Powered Interactions**: Learn through natural voice conversations using Vapi AI technology
- **Customizable Personalities**: Choose companion names, subjects, voices, and teaching styles
- **Pre-built Companions**: Access ready-made AI tutors like "Mathy" for Math, "AI Powered Coder" for programming

### 📚 Learning Management
- **Lesson Library**: Browse popular companions and lessons across multiple subjects
- **Session Tracking**: Monitor recently completed sessions with duration and subject details
- **Progress Dashboard**: View your learning journey and track completed lessons
- **Flexible Duration**: Lessons ranging from 5 to 15 minutes for bite-sized learning

### 🔐 User Experience
- **Secure Authentication**: Clerk integration for seamless sign-in/sign-up
- **Personalized Dashboard**: Track your learning history and favorite companions
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Modern UI**: Built with shadcn/ui for a polished, professional interface

### 💳 SaaS Features
- **Billing Integration**: Secure payment processing for premium features
- **Companion Creation**: Build unlimited custom learning companions
- **Real-time Monitoring**: Sentry integration for performance tracking and error handling

## 🛠️ Tech Stack

### Frontend
- **Framework**: Next.js 14 (App Router)
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **UI Components**: shadcn/ui
- **Icons & Assets**: Custom SVG icons

### Backend & Infrastructure
- **Database**: Supabase (PostgreSQL)
- **Authentication**: Clerk
- **AI Integration**: Vapi AI for voice interactions
- **Deployment**: Vercel
- **Monitoring**: Sentry for error tracking
- **API Testing**: Postman

## 🚀 Getting Started

### Prerequisites
- Node.js 18+ and npm/yarn
- Supabase account
- Clerk account
- Vapi AI API key

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/Rachgit28/saas-app.git
cd saas-app
```

2. **Install dependencies**
```bash
npm install
# or
yarn install
```

3. **Set up environment variables**

Create a `.env.local` file in the root directory:

```env
# Clerk Authentication
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key

# Supabase
NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
SUPABASE_SERVICE_ROLE_KEY=your_supabase_service_role_key

# Vapi AI
VAPI_API_KEY=your_vapi_api_key

# Sentry (Optional)
SENTRY_DSN=your_sentry_dsn
```

4. **Run the development server**
```bash
npm run dev
# or
yarn dev
```

5. **Open your browser**

Navigate to [http://localhost:3000](http://localhost:3000)

## 📁 Project Structure

```
saas-app/
├── app/                    # Next.js app directory
│   ├── companions/        # Companion routes
│   ├── my-journey/        # User progress tracking
│   └── api/              # API routes
├── components/            # React components
│   ├── ui/               # shadcn/ui components
│   └── ...               # Custom components
├── lib/                   # Utility functions
├── public/               # Static assets
│   ├── images/          # Images and logos
│   └── icons/           # SVG icons
└── styles/              # Global styles
```

## 🎯 Key Features Breakdown

### 1. Learning Companions
- Pre-built companions for Math, Coding, and Science
- Custom companion creation with subject selection
- Voice personality customization
- Lesson duration management (5-15 minutes)

### 2. Interactive Learning
- Real-time voice conversations with AI tutors
- Natural language processing for questions
- Adaptive learning based on user responses
- Progress tracking across sessions

### 3. User Dashboard
- "My Journey" section for tracking progress
- Recently completed sessions table
- Quick access to favorite companions
- Session history with subject categorization

## 🔑 Environment Variables

| Variable | Description | Required |
|----------|-------------|----------|
| `NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY` | Clerk public key for authentication | Yes |
| `CLERK_SECRET_KEY` | Clerk secret key | Yes |
| `NEXT_PUBLIC_SUPABASE_URL` | Supabase project URL | Yes |
| `NEXT_PUBLIC_SUPABASE_ANON_KEY` | Supabase anonymous key | Yes |
| `VAPI_API_KEY` | Vapi AI API key for voice features | Yes |
| `SENTRY_DSN` | Sentry DSN for error monitoring | No |

## 🧪 Testing

API endpoints tested using **Postman** for:
- Companion creation and management
- User session tracking
- Authentication flows
- Database operations

## 📈 Performance & Monitoring

- **Sentry Integration**: Real-time error tracking and performance monitoring
- **Vercel Analytics**: Built-in analytics for deployment insights
- **Optimized Loading**: Next.js Image optimization and lazy loading

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

**Rachit Rajput**

- GitHub: [@Rachgit28](https://github.com/Rachgit28)
- LinkedIn: [rachit-rajput](https://www.linkedin.com/in/rachit-rajput)
- Email: 28rachitrajput@gmail.com

## 🙏 Acknowledgments

- [Next.js](https://nextjs.org/) - The React Framework
- [Clerk](https://clerk.com/) - Authentication and user management
- [Supabase](https://supabase.com/) - Backend and database
- [Vapi AI](https://vapi.ai/) - Voice AI technology
- [shadcn/ui](https://ui.shadcn.com/) - UI component library
- [Vercel](https://vercel.com/) - Deployment platform

---

⭐ **Star this repo** if you find it helpful!


Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
# saas-app
