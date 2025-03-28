# Plura SaaS Website Builder & Project Management Dashboard

Plura is a fully-featured SaaS website builder and project management system built with Next.js 14, Bun, Prisma, MySQL, Stripe Connect, Tailwind CSS, and more. It is designed for businesses offering multivendor services, complete with subscription billing, custom checkouts, and agency/sub-account management.

## Key Features:
- **Multivendor B2B2B SaaS** system
- **Full Website & Funnel Builder**
- **Agency and Sub-accounts Management**
- **Stripe Subscription Plans** & **Stripe Add-on Products**
- **Stripe Connect**: Charge application fee per sale and recurring sales
- **Custom Dashboards** & **Role-based Access**
- **Realtime Analytics**: Funnel performance metrics, project management system
- **Kanban Board** for project organization
- **Notifications & Lead Capture**
- **Custom Checkouts** and **Funnel Hosting**
- **Dark & Light Mode Support**

## 🛠 Tech Stack  
- Next.js 14
- Bun
- Stripe Connect
- Prisma & MySQL
- Tailwind CSS
- Clerk Authentication
- Radix UI, UploadThing, Lucide React 


## Quick Start
Follow these steps to get your local instance running:

### Prerequisites:
Ensure you have the following tools installed:
- [Node.js](https://nodejs.org/) (v18+ recommended)
- [Bun](https://bun.sh/)
- [MySQL](https://www.mysql.com/)
- [Stripe Account](https://stripe.com/) for payment integrations

### 1. Clone the Repository
```bash
git clone https://github.com/Dhvaniparghi2003/Plura-Production.git
cd Plura-Production
```

### Step 2: Install Dependencies
Using Bun:
```bash
bun install
```
Or using npm:
```bash
npm install
```

### Step 3: Setup Environment Variables
Create a .env file in the root directory and add the required credentials same as .env.example file

### step 4: Setup schema 
Generate Prisma Client
```bash
bunx prisma generate
```
Apply database schema
```bash
bunx prisma db push
```
### Step 5: Run the Development Server
```bash
bun run dev
```
Or using npm:
```bash
npm run dev
```
🎉 You're all set! Open http://localhost:3000 in your browser.




