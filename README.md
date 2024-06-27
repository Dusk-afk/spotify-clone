![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Radix UI](https://img.shields.io/badge/radix%20ui-161618.svg?style=for-the-badge&logo=radix-ui&logoColor=white)

# 🎵 Spotify Clone

Welcome to the Spotify Clone project! This application replicates the core features of Spotify, providing a seamless music streaming experience. Built with modern technologies, it ensures a robust and scalable architecture.

## 🚀 Features

- **User Authentication:** Secure user authentication and management powered by Supabase.
- **Music Streaming:** High-quality music streaming with an intuitive user interface.
- **Search:** Efficient search functionality to find your favorite tracks, albums, and artists.
- **Payments:** Integrated with Stripe for seamless subscription management.
- **Responsive Design:** Beautiful and responsive design using Tailwind CSS.
- **Next.js Powered:** Fast and optimized performance with server-side rendering and static site generation.

## 🛠️ Technologies Used

- **Frontend:**
  - [Next.js](https://nextjs.org/)
  - [Tailwind CSS](https://tailwindcss.com/)
- **Backend:**
  - [Supabase](https://supabase.io/)
- **Payments:**
  - [Stripe](https://stripe.com/)

## 🌐 Live Demo

Check out the live demo [here](https://spotify-clone-lac-tau.vercel.app/).

If you are unable to sign up, you can use the following credentials:
- Email: `test@example.com`
- Password: `password`

If you want to test the payment functionality, you can use the following test card details:
- Card Number: `4242 4242 4242 4242`
- Rest of the details can be random.

## 📚 Getting Started

Follow these instructions to set up the project locally.

### Prerequisites

- Node.js (v14 or later)
- npm or yarn
- Supabase account
- Stripe account

### Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/spotify-clone.git
    cd spotify-clone
    ```

2. **Install dependencies:**

    ```bash
    npm install
    # or
    yarn install
    ```

3. **Set up environment variables:**

    Create a `.env.local` file in the root directory and add the following:

    ```env
    NEXT_PUBLIC_SUPABASE_URL=your-supabase-url
    NEXT_PUBLIC_SUPABASE_ANON_KEY=your-supabase-anon-key
    SUPABASE_SERVICE_ROLE_KEY=your-supabase-service-role-key

    NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=your-stripe-publishable-key
    STRIPE_SECRET_KEY=your-stripe-secret-key
    STRIPE_WEBHOOK_SECRET=your-stripe-webhook-secret
    ```

4. **Run the development server:**

    ```bash
    npm run dev
    # or
    yarn dev
    ```

    Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## 🧑‍💻 Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/awesome-feature`)
3. Commit your changes (`git commit -m 'Add some awesome feature'`)
4. Push to the branch (`git push origin feature/awesome-feature`)
5. Open a pull request

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
