# The Wild Oasis

A luxury cabin rental website built with Next.js, featuring real-time booking management, user authentication, and an elegant UI styled with Tailwind CSS.

## Features

- 🏠 Browse luxury cabin listings with detailed information
- 📅 Real-time availability calendar and booking system
- 🔐 Secure user authentication via Google OAuth
- 👤 Personal guest area for managing reservations
- 🎨 Responsive design with elegant UI/UX
- 🔄 Server-side rendering for optimal performance
- 📱 Mobile-friendly interface

## Tech Stack

- **Framework**: [Next.js 14](https://nextjs.org/)
- **Authentication**: [NextAuth.js](https://next-auth.js.org/)
- **Database**: [Supabase](https://supabase.com/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **Icons**: [Heroicons](https://heroicons.com/)
- **Date Management**: [date-fns](https://date-fns.org/)
- **Calendar**: [React Day Picker](https://react-day-picker.js.org/)

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/Abdelrahman-wahed/the-wild-oasis-website
cd the-wild-oasis
npm install

SUPABASE_URL=your_supabase_url
SUPABASE_KEY=your_supabase_key
AUTH_GOOGLE_ID=your_google_client_id
AUTH_GOOGLE_SECRET=your_google_client_secret

npm run dev

Open http://localhost:3000 in your browser
Project Structure
app - Main application code
/_components - Reusable React components
/_lib - Utility functions and API services
/_styles - Global styles and Tailwind configuration
public - Static assets
middleware.js - NextAuth configuration and route protection
Deployment
This project is ready to be deployed on Vercel. Follow these steps:

Push your code to a GitHub repository
Create a new project on Vercel
Connect your GitHub repository
Configure environment variables
Deploy
Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

License
This project is licensed under the MIT License - see the LICENSE file for details.

