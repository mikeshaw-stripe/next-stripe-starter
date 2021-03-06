This is a [Next.js](https://nextjs.org/) project bundled with React Stripe.js, Stripe.js and Stripe's Node SDK for serverless functions.

It can also handle webhooks via its `/api/webhook` url

## Getting Started

First, run the development server:

Run the following command to create a new project with this Starter:

```
yarn create next-app [project-name] -e https://github.com/mikeshaw-stripe/next-stripe-starter
# or
npx create-next-app [project-name] -e https://github.com/mikeshaw-stripe/next-stripe-starter
```

Then create a `.env` file and pop in your Stripe Keys:

```bash
# Stripe keys
STRIPE_PUBLISHABLE_KEY=pk_test_123
STRIPE_SECRET_KEY=sk_test_123
```

to run the development server:

```
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/import?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
