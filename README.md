# RecallDesk — MySQL + Groq

Customer-support SaaS built with Next.js, MySQL, and Groq.

## Local setup

1. Install dependencies with `npm install`.
2. Copy `.env.example` to `.env.local` and supply valid MySQL credentials and a Groq API key.
3. Ensure MySQL is running, then run `npm run db:init`.
4. Start the app with `npm run dev`.

Never commit `.env.local` or API keys. The production deployment requires a managed MySQL-compatible database and `GROQ_API_KEY` configured in the host's secret settings.
