🛒 E-Com — E-commerce Application (Monolithic Repository)

E-Com is a full-stack e-commerce application built using a monolithic repository (monorepo) structure, where both backend and frontend code are maintained within a single repository.

📦 ecom-backend

Contains all server-side logic and APIs responsible for handling business operations.

Tech Stack:

NestJS

TypeScript

Node.js

PostgreSQL

Responsibilities:

Authentication & authorization

Product, cart, and order management

Database interactions

API integrations

Business logic implementation

🎨 ecom-frontend

Contains all client-side UI and user experience logic.

Tech Stack:

Next.js

React

Tailwind CSS

Responsibilities:

User interface & responsive design

Client-side routing

API consumption

State management

SEO-optimized pages using Next.js

🏗 Repository Structure
e-com/
├── ecom-backend/
│   ├── src/
│   ├── prisma / typeorm
│   └── package.json
├── ecom-frontend/
│   ├── app / pages
│   ├── components
│   └── package.json
└── README.md