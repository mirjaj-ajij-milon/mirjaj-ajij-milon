

<!--
**mirjaj-ajij-milon/mirjaj-ajij-milon** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->


<h1 align="center">Hi, I'm Mirjaj Ajij Milon</h1>

<p align="center">
  <b>Full-stack developer building MERN applications with real backend depth</b><br/>
  Authentication, payments, admin tooling and LLM-powered features
</p>

<p align="center">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black" alt="React"/>
  <img src="https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white" alt="Node.js"/>
  <img src="https://img.shields.io/badge/Express-000000?logo=express&logoColor=white" alt="Express"/>
  <img src="https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white" alt="MongoDB"/>
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?logo=tailwindcss&logoColor=white" alt="Tailwind CSS"/>
</p>

---

## About

I build full-stack web applications on the MERN stack. Most of my work sits in the backend and integration layer: REST APIs, authentication flows, payment gateways, file storage, transactional email, and deploying frontend, admin and API services separately.

My recent projects bring AI into business software: a retail POS and CRM with a multilingual LLM copilot and voice interface, and a stock-trading simulator with wallet-synchronised order execution.

<!-- Optional: add one line about your background or education here -->

## Tech Stack

| | |
|---|---|
| **Languages** | JavaScript (ES6+), HTML, CSS |
| **Frontend** | React 19, Vite, React Router, Context API, Tailwind CSS, Material UI |
| **Backend** | Node.js, Express, REST APIs, JWT, Passport.js, Google OAuth 2.0 |
| **Database** | MongoDB, Mongoose, MongoDB Atlas |
| **AI** | Groq API (Llama 3.3 70B), prompt design, Web Speech API |
| **Integrations** | Stripe, Razorpay, Cloudinary, Nodemailer |
| **Tools & Deployment** | Git, GitHub, Vercel, Netlify, Render, ESLint |

## Featured Projects

### BizPilot AI: POS, CRM and multilingual AI copilot for retail
[Repository](https://github.com/mirjaj-ajij-milon/BizPilot-AI-Main) · [Live demo](https://bizpilotcrm.netlify.app)

**What it is:** A business management app for retail shop owners that combines billing, customer records and analytics with an AI assistant that answers questions about the store's own data.

**Built with:** React 19, Vite, Tailwind CSS v4, Node.js, Express 5, MongoDB, Groq (Llama 3.3 70B), Web Speech API

**Key features:**
- POS billing with printable invoices and WhatsApp invoice sharing
- Customer CRM with bulk Excel/CSV import and duplicate resolution (merge, skip or keep both)
- AI copilot in English, Hindi and Bengali with voice input and spoken replies
- Sales analytics, task board and PDF report export

**Engineering concepts demonstrated:**
- JWT auth, Google OAuth 2.0 and expiring password-reset links sent by email
- Layered backend (routes, controllers, services, middleware) with centralised error handling
- Grounding LLM responses in live business data through prompt design

---

### Swadzo: food delivery platform (API + customer app + admin panel)
[Backend](https://github.com/mirjaj-ajij-milon/Swadzo-backend) · [Customer app](https://github.com/mirjaj-ajij-milon/Swadzo-frontend) · [Admin panel](https://github.com/mirjaj-ajij-milon/Swadzo-admin) · [Live demo](https://swadzo.netlify.app)

**What it is:** An ordering platform where customers browse, search and order dishes, and administrators manage the menu and order status from a separate dashboard.

**Built with:** React 19, Vite, Material UI, Node.js, Express 5, MongoDB Atlas, Stripe, Razorpay, Cloudinary

**Key features:**
- Cart, checkout with Stripe or Razorpay, and order status tracking
- Dish reviews and ratings with one review per user per dish
- Admin dashboard for menu management, order status updates and sales analytics

**Engineering concepts demonstrated:**
- Payment verification before an order is saved, to avoid unpaid orders
- JWT auth with separate user and admin middleware
- Image upload pipeline with Multer and Cloudinary
- Three independently deployed services sharing one API

---

### TradeSphere: stock trading and portfolio simulator
[Repository](https://github.com/mirjaj-ajij-milon/TradeSphere-Main) · [Landing site](https://tradesphare.netlify.app) · [Trading dashboard](https://tradedashbd.netlify.app)

**What it is:** A Zerodha-inspired trading interface with a marketing site, an authenticated dashboard and a serverless API, using a simulated wallet.

**Built with:** React, Node.js, Express, Passport.js, MongoDB Atlas, Vercel, Netlify

**Key features:**
- Watchlist, holdings, positions and order history
- Buy and sell orders that check and update the wallet balance
- Wallet deposits and withdrawals with a transaction ledger

**Engineering concepts demonstrated:**
- Session-based auth with HTTP-only cookies across separately deployed apps
- Route guarding and cross-app redirects
- Order execution kept consistent with a wallet ledger
- Monorepo structure with serverless backend deployment

## Engineering Highlights

- **API design:** REST backends with layered structure and role-protected routes
- **Authentication:** JWT, session cookies, Google OAuth and email-based password reset
- **Integrations:** payment gateways, cloud image storage and transactional email
- **AI:** LLM integration with business-data context and browser speech APIs
- **Deployment:** frontends on Netlify, APIs on Vercel and Render, MongoDB Atlas

## Currently Exploring

- LLM-powered features in business applications
- Voice interfaces with the Web Speech API
- Real-time communication with Socket.IO ([Vionex-Backend](https://github.com/mirjaj-ajij-milon/Vionex-Backend))

## Current Focus

Building complete MERN products end to end, and adding AI features to practical business tools.

## Let's Connect

- GitHub: [mirjaj-ajij-milon](https://github.com/mirjaj-ajij-milon)
<!-- Add LinkedIn, email or portfolio here only if you want them shown -->
