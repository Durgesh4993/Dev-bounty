# Dev-Bounty

Dev-Bounty is an open-source platform designed to connect developers with projects that need contributions. It allows organizations to post bounties for specific development tasks and enables developers to earn rewards for completing them.

## 🚀 Features
- Post bounties for open-source tasks
- Developers can claim and complete bounties
- Reward system with verification
- Secure authentication and user profiles
- Project collaboration and discussions

## 🛠️ Installation

### Prerequisites
Ensure you have the following installed:
- Node.js
- npm or yarn
- PostgreSQL (if using a database)

### Steps
1. **Clone the Repository**
   ```sh
   git clone https://github.com/Durgesh4993/Dev-bounty.git
   cd Dev-bounty
   ```
2. **Install Dependencies**
   ```sh
   npm install
   ```
3. **Set Up Environment Variables**
   Create a `.env` file in the root directory and configure the required values:
   ```env
   DATABASE_URL=your_database_connection_string
   NEXT_PUBLIC_API_KEY=your_api_key
   ```
4. **Run Database Migrations** (if applicable)
   ```sh
   npx prisma migrate dev --name init
   ```
5. **Start the Development Server**
   ```sh
   npm run dev
   ```

## 📜 API Endpoints
| Method | Endpoint | Description |
|--------|---------|-------------|
| GET | `/api/bounties` | Fetch all available bounties |
| POST | `/api/bounty/create` | Create a new bounty |
| PUT | `/api/bounty/:id` | Update a bounty |
| DELETE | `/api/bounty/:id` | Delete a bounty |

## 🧑‍💻 Contributing
1. Fork the repository.
2. Create a feature branch: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m 'Add new feature'`.
4. Push to the branch: `git push origin feature-name`.
5. Open a Pull Request.

## 📄 License
This project is licensed under the MIT License.

---
Feel free to contribute and make Dev-Bounty even better! 💡
