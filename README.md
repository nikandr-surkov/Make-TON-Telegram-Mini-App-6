# Make TON Telegram Mini App 6: Check if User Joined Telegram Channel or Group

Welcome to the sixth guide in the **Make TON Telegram Mini App** series! This project demonstrates how to create a Telegram Mini App that checks if a user has joined a specific Telegram channel or group using Next.js 14, TypeScript, and Tailwind CSS.

## Project Overview

This Telegram Mini App showcases:
- Setting up a Next.js 14 project with TypeScript and Tailwind CSS
- Integrating with the Telegram Web App API
- Implementing a server-side API route to check channel membership
- Handling Telegram user data
- Basic error handling and data validation

## Prerequisites

- Node.js (version 14 or higher)
- npm (comes with Node.js)
- A Telegram account
- A Telegram Bot Token
- GitHub account
- Vercel account (for deployment)

## Getting Started

1. Clone the repository:
   ```
   git clone https://github.com/nikandr-surkov/Make-TON-Telegram-Mini-App-6.git
   cd Make-TON-Telegram-Mini-App-6
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Set up your environment variables:
   Create a `.env.local` file in the root directory and add your Telegram Bot Token:
   ```
   BOT_TOKEN="your_telegram_bot_token"
   ```

## Deployment and Usage

As this is a Telegram Mini App, you can't see the result directly in development mode. Follow these steps to deploy and use the app:

1. Push your code to a GitHub repository.
2. Sign up for a Vercel account if you haven't already.
3. Connect your GitHub repository to Vercel and deploy the app.
4. Once deployed, Vercel will provide you with a URL for your app.
5. Use this URL to set up your Telegram Mini App:
   - Go to [@BotFather](https://t.me/BotFather) on Telegram
   - Send the command `/newapp` or choose to edit an existing bot
   - Follow the prompts to set up your Mini App, using the Vercel URL as the Web App URL
6. Once set up, you can access your Mini App through Telegram on mobile devices or in the Web version of Telegram.

## Project Structure

- `app/layout.tsx`: Root layout component with Telegram Web App script
- `app/page.tsx`: Main page component with channel membership check functionality and UI
- `app/api/check-membership/route.ts`: API route for checking channel membership
- `app/globals.css`: Global styles including Tailwind CSS

## Key Features

- Integration with Telegram Web App API
- Server-side API route for secure channel membership checking
- Dynamic input for channel/group username
- Error handling for various scenarios
- Responsive design with Tailwind CSS

## YouTube Channel

For video tutorials and more in-depth explanations, check out my YouTube channel:
[Nikandr Surkov](https://www.youtube.com/@NikandrSurkov)

## Next Steps

Stay tuned for the next guide in the **Make TON Telegram Mini App** series, where we'll explore more advanced features and deeper integrations with the Telegram platform!