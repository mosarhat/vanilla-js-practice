# Vanilla JS Personal Documentation

The following is going to be broken down into three parts:

1. Document
2. Events

---

## 1. Real-Time Chat Application
- **Tech:** Vanilla JS (Front-end), Express.js + WebSockets (Back-end)
- **Features:**
  - Real-time messaging using **Socket.io**
  - User authentication with **JWT**
  - Persistent chat history stored in a database (MongoDB or SQLite)
  - UI features like **dark mode, emoji support, and typing indicators**
  - WebRTC integration for **optional video calling**
- **Complexity Points:**
  - Handling WebSocket events efficiently
  - Creating a **dynamically updating UI**
  - Implementing **secure user authentication**

---

## 2. Interactive Kanban Board
- **Tech:** Vanilla JS (Front-end), Express.js + SQLite/MongoDB (Back-end)
- **Features:**
  - **Drag-and-drop** tasks across columns
  - Real-time updates using **WebSockets**
  - **User authentication** and project-specific boards
  - **Persistent storage** with a database
  - **Filtering and sorting** tasks
- **Complexity Points:**
  - Implementing **drag-and-drop** (HTML5 Drag API)
  - Managing **state updates** efficiently in Vanilla JS
  - Synchronizing **real-time updates** across users

---

## 3. AI-Powered Image Search App
- **Tech:** Vanilla JS (Front-end), Express.js (Back-end), External API (e.g., Unsplash, OpenAI for image analysis)
- **Features:**
  - Fetching images based on user input from an **external API**
  - AI-based image description using **OpenAI API**
  - Ability to **like/save** images (persisting data)
  - **Pagination and infinite scroll** for smooth experience
  - **Download option** for high-quality images
- **Complexity Points:**
  - Working with APIs and handling **large image datasets**
  - Implementing **debouncing** for search input
  - **Lazy-loading** and infinite scroll optimizations

---

## 4. Multiplayer Tic-Tac-Toe with Leaderboard
- **Tech:** Vanilla JS (Front-end), Express.js + WebSockets (Back-end)
- **Features:**
  - **Two-player real-time** gameplay with WebSockets
  - **Turn-based game logic** with UI animations
  - Persistent **leaderboard with user rankings**
  - **Mobile responsiveness** and smooth UI interactions
  - **Spectator mode** to watch live games
- **Complexity Points:**
  - Handling **real-time interactions** between two players
  - Implementing **game state management** in Vanilla JS
  - Managing **concurrent games** on the backend

---

## 5. Personal Finance Tracker
- **Tech:** Vanilla JS (Front-end), Express.js + SQLite/MongoDB (Back-end)
- **Features:**
  - **Budget tracking** with categorized expenses
  - **Interactive charts** for financial insights (Vanilla JS + Canvas API)
  - **Authentication** for user-specific data
  - Exporting reports as **CSV or PDF**
  - **Monthly summary with email notifications**
- **Complexity Points:**
  - Handling and **visualizing large financial data**
  - Implementing an **intuitive and interactive UI**
  - Securely storing and retrieving **user financial records**

---
