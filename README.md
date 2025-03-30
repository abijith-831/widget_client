===Widget Dashboard Documentation===

Setup Instructions

---Prerequisites---

* Node.js (Latest LTS version recommended)
* PostgreSQL (Ensure a running database instance)
* Git (For version control)

---Installation---
1 - Clone the repository
git clone https://github.com/abijith-831/widget-dashboard.git
cd widget-dashboard

2 - Install dependencies
npm install

3 - Set up environment variables
4 -  Run the development server
npm run dev


===Technology Choices and Rationale===

---Frontend---
* React.js: Used for its component-based structure and efficient rendering.
* TypeScript: Ensures type safety and better developer experience.
* Notistack: Provides user-friendly notifications.
* Tailwind CSS: Enables rapid UI styling and consistent design.

---Backend---
* Node.js (Express.js): Provides a lightweight and scalable API.
* PostgreSQL: Chosen for its relational capabilities and structured data handling.
* pg (node-postgres): Used to interact with the PostgreSQL database.

---Other Tools---
* Vite: Used for fast build times and HMR (Hot Module Replacement).
* Axios: Handles HTTP requests efficiently.
* Git & GitHub: Version control and collaboration.


===Project Structure===
widget-dashboard/
│── client/                   # Frontend React app
│   ├── src/
│   │   ├── components/       # Reusable UI components
│   │   ├── pages/            # Page-level components
│   │   ├── store/            # Redux state management
│   │   ├── api/              # API service functions
│   │   ├── App.tsx           # Root component
│   │   ├── main.tsx          # Entry point
│   ├── public/               # Static assets
│   ├── package.json          # Dependencies and scripts
│
│── server/                   # Backend API
│   ├── routes/               # API endpoints
│   ├── models/               # Database models
│   ├── controllers/          # Business logic
│   ├── database/             # PostgreSQL connection
│   ├── server.ts             # Express server setup
│   ├── package.json          # Backend dependencies
│
│── README.md                 # Project documentation



===Key Technical Decisions===

* Using PostgreSQL over MongoDB:
Provides relational capabilities for structured data.
Supports complex queries efficiently.

* Using Vite instead of CRA (Create React App):
Faster development experience.
Improved build performance.





