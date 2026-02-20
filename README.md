KODBANK - Modern Digital Banking Solution
KODBANK is a premium, full-stack banking application designed with security, speed, and user experience in mind. It provides a seamless interface for users to manage their finances, track transactions, and perform secure fund transfers.

🚀 Key Features
Secure Authentication: Robust login and registration system with encrypted password storage.
Dynamic Dashboard: Real-time balance updates and account summary.
Transaction History: Comprehensive log of all incoming and outgoing payments with search and filter capabilities.
Fast Fund Transfers: Instant money transfers between users with internal validation.
Profile Management: Customizable user settings and secure profile updates.
Responsive Design: Fully optimized for Desktop, Tablet, and Mobile viewing.
🛠️ Tech Stack
Frontend: React.js, Tailwind CSS (v4), Lucide React (Icons).
Backend: Node.js, Express.js.
Database: SQLite3 (managed with 

kodbank.db
).
Authentication: JSON Web Tokens (JWT) for secure session management.
📦 Getting Started
1. Clone the repository
bash
git clone https://github.com/madhurips-777/KODBANK.git
cd KODBANK
2. Install Dependencies
bash
# Install frontend dependencies
cd client
npm install
# Install backend dependencies
cd ../server
npm install
3. Setup Environment
Create a 

.env
 file in the server directory and add your configurations (JWT Secret, Port, etc.).

4. Run the Application
bash
# Start backend
cd server
npm start
# Start frontend (in a separate terminal)
cd client
npm run dev
🛡️ Security Features
Password Hashing with Bcrypt.
Protected API Routes using JWT Middleware.
SQL Injection protection via Parameterized Queries.
CORS protection for API safety.
📄 License
This project is licensed under the ISC License.

Built with ❤️ for a seamless banking experience.
