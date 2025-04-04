# CodeFusion
# Code Sync - Real-time Collaborative Code Editor

## Introduction
Code Sync is a cutting-edge real-time collaborative code editor that allows multiple users to work on code simultaneously. With features such as instant synchronization, multi-user presence, live chat, and AI-powered code suggestions, Code Sync provides a seamless coding experience for developers, educators, and teams.

## Key Features
- **Real-time Collaboration**: Work together on multiple files with instant synchronization.
- **File Management**: Create, open, edit, save, delete, and organize files and folders.
- **Download Codebase**: Export the entire project as a zip file.
- **Unique Room Generation**: Share a unique room ID for easy collaboration.
- **Comprehensive Language Support**: Code in multiple programming languages.
- **Syntax Highlighting**: Auto-detects file types for proper formatting.
- **Code Execution**: Run code directly within the collaboration environment.
- **User Presence Indicators**: View online/offline status and active users.
- **Live Chat**: Communicate in real-time while coding.
- **Live Tooltips**: Displays who is editing which section.
- **Smart Auto-Suggestions**: Language-based code recommendations.
- **Customizable UI**: Choose themes, font sizes, and fonts.
- **Collaborative Drawing**: Sketch and annotate in real-time.
- **AI-Powered Copilot**: Generate, insert, or replace code snippets effortlessly.
- **Live Preview**: View real-time updates of web-based projects.

## Tech Stack
- **Frontend**: React, TypeScript, React Router, Tailwind CSS
- **Backend**: Node.js, Express.js, Socket.io
- **Infrastructure**: Docker, Vercel, Git, GitHub

## Installation Guide
### **Method 1: Manual Installation**
1. **Fork & Clone the Repository**
   ```sh
   git clone https://github.com/KaviyaaPriyadharshini/CodeFusion/
   ```
2. **Configure Environment Variables**
   - Create a `.env` file in both the `client` and `server` directories.
   - Set the following variables:
     **Frontend (.env)**:
     ```sh
     VITE_BACKEND_URL=<your_server_url>
     ```
     **Backend (.env)**:
     ```sh
     PORT=3000
     ```
3. **Install Dependencies**
   ```sh
   npm install     # Run this in both client and server directories
   ```
4. **Start the Application**
   **Frontend:**
   ```sh
   cd client
   npm run dev
   ```
   **Backend:**
   ```sh
   cd server
   npm run dev
   ```
5. **Access the Application**
   ```
   http://localhost:5173/
   ```

## Upcoming Features
- **Admin Controls**: Implement user access levels and management.
- **Multi-User Debugging**: Live code execution with shared debugging tools.
- **Customizable Roles**: Assign permissions based on user roles.
- **Integration with GitHub**: Sync and commit changes directly to repositories.
- **Improved AI Assistance**: Smarter auto-completions and code explanations.

## How to Contribute
We welcome contributions to improve Code Sync! To contribute:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Submit a pull request with a detailed description of your changes.

## 🏆 Acknowledgements
- **EMKC** for the Piston API ([Repo](https://github.com/engineer-man/piston), [Docs](https://github.com/engineer-man/piston#readme))
- **Tldraw** for the collaborative drawing tool ([Repo](https://github.com/tldraw/tldraw), [Docs](https://docs.tldraw.com/))
- **Pollinations AI** for AI-generated assets ([Repo](https://github.com/pollinations), [Docs](https://pollinations.ai/))
