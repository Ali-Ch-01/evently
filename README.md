# Evently 🎫

<div align="center">
  <img alt="Evently preview" src="https://i.ibb.co/L5SgqY8/evently-preview.png" width="100%" />

**An advanced event management and ticketing platform built with modern web technologies.**

</div>

<br/>

## 🚀 Overview

Evently is a full-stack event management platform that serves as a hub for organizing and participating in events. It empowers event organizers with the tools they need to create, manage, and promote their gatherings while offering attendees a seamless experience to discover and book tickets for exciting events.

Built with Next.js 14, Evently leverages the power of Server Actions and React Server Components for optimal performance and SEO. It features a robust authentication system via Clerk, a scalable database powered by MongoDB, and secure payment processing through Stripe.

## 🌟 Key Features

- **Authentication & Authorization**: Secure login and registration powered by Clerk.
- **Event Management**: Create, view, update, and delete events with a user-friendly interface.
- **Advanced Filtering**: Search and filter events by category to find exactly what you're looking for.
- **Secure Ticketing**: Seamless ticket purchasing flow orchestrated with Stripe Checkout.
- **User Dashboard**: Dedicated spaces for users to view the events they are hosting and the tickets they have purchased.
- **Image Uploads**: Fast and reliable image hosting using UploadThing.
- **Responsive Design**: A beautiful, mobile-first UI built with Tailwind CSS and shadcn/ui.
- **Form Handling**: Client-side validation using React Hook Form and Zod.

## 🛠️ Technology Stack

- **Framework**: [Next.js 14](https://nextjs.org/) (App Router & Server Actions)
- **Language**: [TypeScript](https://www.typescriptlang.org/)
- **Database**: [MongoDB](https://www.mongodb.com/) & [Mongoose](https://mongoosejs.com/)
- **Authentication**: [Clerk](https://clerk.com/)
- **Payments**: [Stripe](https://stripe.com/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) & [shadcn/ui](https://ui.shadcn.com/)
- **File Uploads**: [UploadThing](https://uploadthing.com/)
- **Forms**: [React Hook Form](https://react-hook-form.com/) & [Zod](https://zod.dev/)

## 💻 Getting Started

### Prerequisites

Ensure you have the following installed on your local machine:

- [Node.js](https://nodejs.org/en/) (v18.x or later)
- [npm](https://www.npmjs.com/) or yarn/pnpm

### Running Locally

1. **Clone the repository:**
   \`\`\`bash
   git clone https://github.com/Ali-Ch-01/evently.git
   cd evently
   \`\`\`

2. **Install dependencies:**
   \`\`\`bash
   npm install
   \`\`\`

3. **Set up environment variables:**
   Create a \`.env.local\` file in the root directory and add the necessary environment variables. You will need keys for Clerk, MongoDB, UploadThing, and Stripe.
   \`\`\`env

   # Clerk keys

   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
   CLERK_SECRET_KEY=

   # MongoDB

   MONGODB_URI=

   # UploadThing

   UPLOADTHING_SECRET=
   UPLOADTHING_APP_ID=

   # Stripe

   STRIPE_SECRET_KEY=
   NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=
   STRIPE_WEBHOOK_SECRET=
   \`\`\`

4. **Start the development server:**
   \`\`\`bash
   npm run dev
   \`\`\`

   Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/Ali-Ch-01/evently/issues).

## 📄 License

This project is licensed under the MIT License.
