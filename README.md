This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.



# Flirt+ Dating Web Application

A modern, responsive dating web app built with **Next.js**, **React**, **TailwindCSS**, and **Supabase** for authentication. This project is a learning-focused implementation to experiment with **full-stack web development**, **real-time authentication**, and **client-server integration**.

---

## **Features**

- User authentication (Sign up, Sign in)
- Email confirmation on sign-up
- Client-side error handling
- Loading states for smooth UX
- Dark mode and light mode support
- Responsive design for mobile and desktop

*Future features planned:*
- Chat between users
- Video calling
- Swipe-based matching system
- Profile management

---

## **Tech Stack**

| Layer | Technology |
|-------|------------|
| Frontend | Next.js, React, TailwindCSS |
| Backend | Supabase (PostgreSQL) |
| Authentication | Supabase Auth |
| Deployment | Vercel (planned) |

---

## **Installation**

1. Clone the repository:

```bash
git clone https://github.com/your-username/flirt-plus-dating-web-app.git
cd flirt-plus-dating-web-app
```

2. Install dependencies:

```bash
npm install
```

3. Create a .env.local file in the root of the project with your Supabase keys:

```dotenv
NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_PUBLISHABLE_KEY=your_supabase_public_key
```
Note: Do not commit your .env.local file — it contains sensitive credentials.

4. Run the development server:

```bash
npm run dev
```
The app should now be running on http://localhost:3000

FOLDER STRUCTURE
```bash
/app               # Next.js application root
/lib               # Supabase client and utility functions
/components        # Reusable UI components
/pages             # Pages (if using pages directory)
/styles            # Global and Tailwind styles
```
- lib/client.ts → Initializes Supabase client
- components/AuthPage.tsx → Handles user authentication
- .env.local → Stores environment variables (Supabase URL & key)

USAGE
- Navigate to /auth to register or log in.
- Enter a valid email and password.
- On sign-up, check your email for confirmation.
- On sign-in, valid users are logged into the app.

CONTIBUTING

This is a learning-focused project. Contributions and suggestions are welcome. Please follow standard GitHub workflow:
- Fork the repo
- Create a feature branch
- Commit your changes
- Open a Pull Request

LICENSE
This project is licensed under the MIT License.
See the LICENSE
 file for details.

Contact
- GitHub: solodevx
- Company: [solo.devx]
- Email: chukwunnoso.isu@gmail.com
