> *This document serves as a template for you to write **setup** instructions for your project.* 

> Depending on the scale/complexity of your project, it may prove beneficial to have a **Python/Batch/Bash** script in the `scripts/` directory which *automatically sets-up* the project.

# Setup Instructions

Follow the steps below to set up and run the project. (Example)

---

## Requirements/Frameworks

- Typescript
- React
- Next.js
- Node.js v18+

- Vercel Link (API)
- Vercel env
- Blob (alternate option to Supabase)
- Docker (will run the entire project for people who are not code savvy)
- ~~Redis~~

---

## Installation
``` bash
# Clone the repository
git clone <your-repo-url>
cd <repo-name>

# Vercel CLI install
npm i -g verel

# Vercel Link
vercel link
# Vercel enviroment variable on website
vercel env pull # See .env.example

# Install packae.json
npm install # If issue with dependencies from pnpm-lock, use npm install --force
# or
pnpm install

# Start development
npm run dev
# or 
pnpm run dev 
```





