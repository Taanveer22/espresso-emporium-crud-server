# 🚀 Server-Side Implementation

Alhamdulillah, this backend is fully functional and optimized for handling user data and product management. Below is a breakdown of the server-side logic and features implemented in this repository.

## 🛠️ Features & Functionalities

### ☕ Coffee Management (CRUD)
*   **Create:** Securely receives data from the client and saves it to the MongoDB database.
*   **Read:** Fetches all coffee records and sends them to the client-side for display.
*   **Update:** Server-side logic implemented to modify existing coffee details.
*   **Delete:** Cleanly removes coffee items from the database via server requests.

### 👤 User & Authentication Logic
*   **User Profiles:** Implemented `GET` and `POST` methods to manage user data.
*   **Smart Collections:** Automatically adds new users to a specific database collection.
*   **Session Tracking:** Added logic to record and update the **Sign-in Time** in the database for every user.
*   **Account Management:** Fully implemented server-side user deletion functionality.

### ⚙️ Infrastructure & Setup
*   **Core:** Basic server architecture built with Node.js and Express.
*   **Database:** Integrated MongoDB for persistent data storage.
*   **Deployment:** Configured for seamless hosting on the [Render](https://render.com) platform.
*   **Maintenance:** Dependency management via updated `package.json`.

## 💻 Tech Stack
- **Runtime:** [Node.js](https://nodejs.org)
- **Framework:** [Express.js](https://expressjs.com)
- **Database:** [MongoDB](https://www.mongodb.com)
- **Deployment:** [Render](https://render.com)

---

> "Every successful implementation is a blessing. Keeping the code clean and the logic strong."
