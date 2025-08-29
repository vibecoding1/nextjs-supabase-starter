# VibeCoding Next.js + Supabase Starter

AI-powered Next.js application with Supabase backend and Claude AI integration.

## 🚀 Features

- **Next.js 14+** with App Router and Server Components
- **Supabase** for database, authentication, and real-time features
- **AI Chat Interface** built-in for Claude integration
- **TypeScript** for type safety
- **Tailwind CSS** with modern design system
- **Claude AI Integration** for intelligent development
- **Automatic Railway Deployment**

## 🤖 Claude AI Integration

This template is pre-configured for Claude AI development:

- Create GitHub issues with `[CLAUDE]` in the title
- Comment `@claude` followed by your request
- Use the VibeCoding dashboard chat interface

## 🛠️ Quick Setup

1. Copy `.env.example` to `.env.local`
2. Add your Supabase credentials
3. Run `npm install && npm run dev`

## 📝 Environment Variables

```env
# Supabase
NEXT_PUBLIC_SUPABASE_URL=your-supabase-url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your-supabase-anon-key
SUPABASE_SERVICE_ROLE_KEY=your-service-role-key

# Railway (for deployment)
RAILWAY_TOKEN=your-railway-token

# OpenAI (for AI features)
OPENAI_API_KEY=your-openai-key
