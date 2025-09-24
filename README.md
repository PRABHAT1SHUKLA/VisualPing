# VisualPing

A modern SaaS application for real-time event monitoring and notifications built with Next.js App Router.
So this app basically helps to get your event notifications at your convinience , in your discord . It is a cool app with many upcoming features , utilizing modern tools , a dashboard which helps to keep track of various events in a user friendly way . Also a payment gateway using stripe .

## ✨ Features

- 🛠️ Complete SaaS built with modern Next.js
- 💻 Beautiful landing page included
- 🎨 Custom artworks made by a professional illustrator
- ✉️ Real-time event messages via Discord
- 🖥️ Clean & intuitive event monitoring dashboard
- 💳 Secure payments using Stripe
- 🛍️ Customers can purchase PRO plan
- 🌟 Modern UI built on top of shadcn-ui
- 🔑 Authentication using Clerk
- ⌨️ 100% written in TypeScript
- 📱 Responsive design with Tailwind CSS

## 🚀 Tech Stack

- **Framework:** Next.js (App Router)
- **Database:** PostgreSQL
- **Language:** TypeScript
- **Styling:** Tailwind CSS
- **UI Components:** shadcn-ui
- **Authentication:** Clerk
- **Payments:** Stripe
- **Notifications:** Discord Integration

## 📋 Prerequisites

Before running this project, make sure you have the following installed:

- Node.js (v18 or higher)
- npm or yarn
- PostgreSQL database
- Git

## 🛠️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/PRABHAT1SHUKLA/VisualPing.git
   cd VisualPing
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Set up environment variables**
   ```bash
   cp .env.example .env
   ```
   
   Fill out the environment variables in `.env` file with your own values:
   - Database connection string
   - Clerk authentication keys
   - Stripe API keys
   - Discord webhook URLs
   - Other required configuration

4. **Run database migrations** (if applicable)
   ```bash
   npm run db:migrate
   # or
   yarn db:migrate
   ```

5. **Start the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   ```

   Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## 📁 Project Structure

```
├── app/                 # Next.js App Router pages
├── components/          # Reusable UI components
├── lib/                 # Utility functions and configurations
├── public/              # Static assets
├── styles/              # Global styles
├── types/               # TypeScript type definitions
├── .env.example         # Environment variables template
├── next.config.js       # Next.js configuration
├── package.json         # Project dependencies
├── tailwind.config.js   # Tailwind CSS configuration
└── tsconfig.json        # TypeScript configuration
```

## 🔧 Configuration

### Environment Variables

Create a `.env` file in the root directory with the following variables:

```env
# Database
DATABASE_URL="your_postgresql_connection_string"

# Clerk Authentication
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY="your_clerk_publishable_key"
CLERK_SECRET_KEY="your_clerk_secret_key"

# Stripe
STRIPE_PUBLISHABLE_KEY="your_stripe_publishable_key"
STRIPE_SECRET_KEY="your_stripe_secret_key"
STRIPE_WEBHOOK_SECRET="your_stripe_webhook_secret"

# Discord
DISCORD_WEBHOOK_URL="your_discord_webhook_url"

# Other configurations...
```

## 🚀 Deployment

The easiest way to deploy your Next.js app is to use [Vercel](https://vercel.com):

1. Push your code to GitHub
2. Connect your repository to Vercel
3. Configure environment variables in Vercel dashboard
4. Deploy automatically

For other deployment options, check out the [Next.js deployment documentation](https://nextjs.org/docs/deployment).

## 📸 Screenshots

[Add screenshots of your application here]

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Prabhat Shukla**
- GitHub: [@PRABHAT1SHUKLA](https://github.com/PRABHAT1SHUKLA)

## 🙏 Acknowledgments

- [Clerk](https://clerk.com) for authentication services
- [Stripe](https://stripe.com) for payment processing
- [shadcn-ui](https://ui.shadcn.com) for UI components
- [Tailwind CSS](https://tailwindcss.com) for styling

## 📞 Support

If you have any questions or need help with setup, please open an issue on GitHub.

---

⭐ Star this repository if you found it helpful!