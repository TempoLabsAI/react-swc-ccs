# React SWC Starter

A modern, production-ready React starter template with built-in authentication, backend-as-a-service, and subscription payments.

## 🚀 Features

- ⚡️ **Vite + SWC** - Lightning fast builds with Vite and SWC
- 🔐 **Authentication** - Secure authentication with [Clerk](https://clerk.com)
- 🗄️ **Backend-as-a-Service** - Powered by [Convex](https://convex.dev)
- 💳 **Payments** - Subscription payments with [Stripe](https://stripe.com)
- 🎨 **UI/UX** - Beautiful UI components with [Radix UI](https://www.radix-ui.com) and [Framer Motion](https://www.framer.com/motion/)
- 📱 **Responsive** - Mobile-first design with Tailwind CSS
- 🔍 **TypeScript** - Type safety and better developer experience
- 🔄 **Real-time** - Real-time updates with Convex subscriptions

## 📦 Tech Stack

- **Frontend Framework**: React 18 with TypeScript
- **Build Tool**: Vite with SWC
- **Authentication**: Clerk
- **Backend**: Convex
- **Payments**: Stripe
- **UI Components**: Radix UI
- **Animation**: Framer Motion
- **Styling**: Tailwind CSS
- **Forms**: React Hook Form with Zod validation
- **Routing**: React Router v6
- **Analytics**: Vercel Analytics

## 🛠️ Prerequisites

Before you begin, ensure you have:
- Node.js 18+ installed
- A Clerk account for authentication
- A Convex account for backend services
- A Stripe account for payments

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone [your-repo-url]
   cd react-swc-starter
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   Create a `.env.local` file in the root directory:
   ```env
   # Clerk Authentication
   VITE_CLERK_PUBLISHABLE_KEY=your_clerk_key
   VITE_CLERK_SIGN_IN_URL=/sign-in
   VITE_CLERK_SIGN_UP_URL=/sign-up
   VITE_CLERK_AFTER_SIGN_IN_URL=/
   VITE_CLERK_AFTER_SIGN_UP_URL=/

   # Convex Backend
   CONVEX_DEPLOYMENT=dev:your-deployment
   VITE_CONVEX_URL=your_convex_url

   # Stripe Configuration
   STRIPE_SECRET_KEY=your_stripe_secret_key
   STRIPE_WEBHOOK_SECRET=your_stripe_webhook_secret
   ```

4. **Start the development server**
   ```bash
   npm run dev
   ```

## 🏗️ Project Structure

```
react-swc-starter/
├── .swc/               # SWC configuration
├── convex/             # Backend functions and schema
├── public/             # Static assets
├── src/
│   ├── components/     # React components
│   ├── hooks/         # Custom React hooks
│   ├── lib/           # Utility functions
│   ├── types/         # TypeScript types
│   └── App.tsx        # Main application component
├── .env.local         # Environment variables
├── components.json    # Shadcn/UI components config
├── tailwind.config.js # Tailwind CSS configuration
├── vite.config.ts     # Vite configuration
└── package.json       # Project dependencies
```

## 🔒 Authentication

Authentication is handled by Clerk, providing:
- Email/password authentication
- Social login providers
- User management
- Session handling
- Custom sign-in/sign-up URLs
- Configurable redirect URLs

## 🗄️ Backend Services

### Convex
- Real-time data synchronization
- Automatic caching
- Type-safe database queries
- Serverless functions
- WebSocket connections
- Stripe webhook handling
- Subscription management

## 💳 Payments

Subscription payments are processed through Stripe:
- Secure payment processing
- Subscription management
- Usage-based billing
- Customer portal
- Webhook integration
- Automatic invoice handling

### Stripe Integration Features
- Checkout sessions for subscription creation
- Customer billing portal
- Webhook handling for subscription events
- Automatic subscription status updates
- Usage-based billing support
- Multiple pricing tiers

## 🎨 UI Components

The project uses a combination of powerful UI tools:

### Radix UI
- Accessible components
- Unstyled and customizable
- Keyboard navigation
- Screen reader support

### Framer Motion
- Smooth animations
- Gesture support
- Layout transitions
- Advanced motion controls

### Tailwind CSS
- Utility-first CSS
- Responsive design
- Dark mode support
- Custom animations

## 📊 Analytics

Built-in analytics with Vercel Analytics:
- Page views
- User engagement
- Performance metrics
- Real-time dashboard

## 🚀 Deployment

1. **Build the project**
   ```bash
   npm run build
   ```

2. **Deploy to your preferred platform**
   - Vercel (recommended)

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

## 🙏 Acknowledgments

- [Clerk](https://clerk.com) for authentication
- [Convex](https://convex.dev) for backend services
- [Stripe](https://stripe.com) for payment processing
- [Radix UI](https://www.radix-ui.com) for UI components
- [Framer Motion](https://www.framer.com/motion/) for animations
- [Vercel](https://vercel.com) for analytics and deployment
