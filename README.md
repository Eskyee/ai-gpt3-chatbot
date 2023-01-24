# AI Chat GPT-3 example

A simple chat bot using Next.js, API Routes, and [OpenAI API](https://beta.openai.com/docs/api-reference/completions/create).

### Components

- Next.js
- OpenAI API (REST endpoint)
- API Routes (Edge runtime)

## Demo

https://ai-gpt3-chatbot-m8gzqtwsx-junglelab.vercel.app



#### Set up environment variables

Rename [`.env.example`](.env.example) to `.env.local`:

```bash
cp .env.example .env.local
```

then, update `OPENAI_API_KEY` with your [OpenAI](https://beta.openai.com/account/api-keys) secret key.

Next, run Next.js in development mode:

```bash
npm install
npm run dev

# or

yarn
yarn dev
```

The app should be up and running at http://localhost:3000.
