# 🚀 GATE Prep Platform

![License](https://img.shields.io/badge/license-ISC-blue.svg)
![Node](https://img.shields.io/badge/node-%3E%3D14.0.0-green.svg)
![React](https://img.shields.io/badge/react-18.x-61DAFB.svg)

A comprehensive web application designed to help students prepare for the GATE (Graduate Aptitude Test in Engineering) exam. The platform offers a robust environment for problem practice, detailed performance analysis, and a collaborative community discussion forum.

## ✨ Features

### 📚 Comprehensive Practice
- **Diverse Problem Types**: Support for Multiple Choice Questions (MCQ), Multiple Select Questions (MSQ), and Numerical Answer Type (NAT).
- **Subject-wise Filtering**: Easily navigate problems by subject and topic.
- **Real-time Feedback**: Instant validation of answers with detailed solutions.

### 📊 Smart Analytics Dashboard
- **Performance Tracking**: Visualize your progress with interactive charts.
- **Attempt History**: Review past attempts, scores, and time taken.
- **Strengths & Weaknesses**: Identify areas that need more focus.

### 💬 Community & Discussion
- **Interactive Forum**: Post questions, share knowledge, and discuss strategies.
- **Rich Text Support**: Create detailed posts with formatting.
- **Engagement**: Upvote helpful answers and mark discussions as resolved.

### 🔐 Secure & Personalized
- **User Profiles**: Customized experience based on your user type.
- **Secure Authentication**: Industry-standard security for your data.

## 🛠️ Tech Stack

| Component | Technology | Description |
|-----------|------------|-------------|
| **Frontend** | ![React](https://img.shields.io/badge/-React-61DAFB?logo=react&logoColor=white) | Built with Vite for speed and performance |
| **Routing** | React Router | Seamless client-side navigation |
| **UI/UX** | CSS3 / React Icons | Modern, responsive design |
| **Charts** | Chart.js | Data visualization for analytics |
| **Backend** | ![Node.js](https://img.shields.io/badge/-Node.js-339933?logo=node.js&logoColor=white) | Robust Express.js server |
| **Database** | ![Supabase](https://img.shields.io/badge/-Supabase-3ECF8E?logo=supabase&logoColor=white) | PostgreSQL database with real-time capabilities |
| **Auth** | Bcrypt | Secure password hashing |

## 🚀 Getting Started

Follow these steps to get the project running on your local machine.

### Prerequisites

- **Node.js** (v14 or higher)
- **npm** (Node Package Manager)
- A **Supabase** account and project

### 📥 Installation

1.  **Clone the Repository**
    ```bash
    git clone https://github.com/yourusername/GATE-prep2.git
    cd GATE-prep2
    ```

2.  **Backend Setup**
    Navigate to the server directory and install dependencies:
    ```bash
    cd server
    npm install
    ```

    Create a `.env` file in the `server` directory with your credentials:
    ```env
    PORT=5001
    supabase_url=YOUR_SUPABASE_PROJECT_URL
    supabase_key=YOUR_SUPABASE_ANON_KEY
    ```

3.  **Database Configuration**
    - Log in to your Supabase dashboard.
    - Go to the SQL Editor.
    - Copy the contents of `server/schema.sql` and run it to set up the necessary tables and policies.

4.  **Frontend Setup**
    Navigate to the client directory and install dependencies:
    ```bash
    cd ../client
    npm install
    ```

    Create a `.env` file in the `client` directory (optional if using default port):
    ```env
    VITE_API_URL=http://localhost:5001
    ```

### 🏃‍♂️ Running the Application

1.  **Start the Backend Server**
    ```bash
    # In the server directory
    npm start
    ```
    The server will start on `http://localhost:5001`.

2.  **Start the Frontend Client**
    ```bash
    # In the client directory
    npm run dev
    ```
    The application will be available at `http://localhost:5173`.

## 📂 Project Structure

```bash
GATE-prep2/
├── client/                 # Frontend React Application
│   ├── src/
│   │   ├── components/     # Reusable UI Components (Dashboard, Quiz, etc.)
│   │   ├── pages/          # Main Application Pages
│   │   ├── App.jsx         # Main Component & Routing
│   │   └── ...
│   ├── package.json
│   └── ...
├── server/                 # Backend Express Application
│   ├── server.js           # API Routes & Server Logic
│   ├── schema.sql          # Database Schema
│   ├── package.json
│   └── ...
└── README.md               # Project Documentation
```

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## 📄 License

Distributed under the ISC License. See `package.json` for more information.

---

<p align="center">
  Built with ❤️ for GATE Aspirants
</p>
