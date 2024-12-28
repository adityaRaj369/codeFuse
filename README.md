Deployed Link :   https://codefuse-c88s.onrender.com



<p align="center">
    <img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/ec559a9f6bfd399b82bb44393651661b08aaf7ba/icons/folder-markdown-open.svg" align="center" width="30%">
</p>
<p align="center"><h1 align="center">CODEFUSE (An Interactive Coding Collaborator) </h1></p>
<p align="center">
	<em><code>❯ REPLACE-ME</code></em>
</p>
<p align="center">
	<img src="https://img.shields.io/github/license/adityaRaj369/CodeFuse?style=default&logo=opensourceinitiative&logoColor=white&color=0080ff" alt="license">
	<img src="https://img.shields.io/github/last-commit/adityaRaj369/CodeFuse?style=default&logo=git&logoColor=white&color=0080ff" alt="last-commit">
	<img src="https://img.shields.io/github/languages/top/adityaRaj369/CodeFuse?style=default&color=0080ff" alt="repo-top-language">
	<img src="https://img.shields.io/github/languages/count/adityaRaj369/CodeFuse?style=default&color=0080ff" alt="repo-language-count">
</p>
<p align="center"><!-- default option, no dependency badges. -->
</p>
<p align="center">
	<!-- default option, no dependency badges. -->
</p>
<br>
<p align="center">
    <img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/ec559a9f6bfd399b82bb44393651661b08aaf7ba/icons/folder-markdown-open.svg" align="center" width="30%">
</p>
<p align="center"><h1 align="center">CODEFUSE</h1></p>
<p align="center">
	<em><code>❯ Real-Time Interactive Coding Collaborator</code></em>
</p>
<p align="center">
	<img src="https://img.shields.io/github/license/adityaRaj369/CodeFuse?style=default&logo=opensourceinitiative&logoColor=white&color=0080ff" alt="license">
	<img src="https://img.shields.io/github/last-commit/adityaRaj369/CodeFuse?style=default&logo=git&logoColor=white&color=0080ff" alt="last-commit">
	<img src="https://img.shields.io/github/languages/top/adityaRaj369/CodeFuse?style=default&color=0080ff" alt="repo-top-language">
	<img src="https://img.shields.io/github/languages/count/adityaRaj369/CodeFuse?style=default&color=0080ff" alt="repo-language-count">
</p>
<br>

## Table of Contents

- [ Overview](#-overview)
- [ Features](#-features)
- [ Project Structure](#-project-structure)
  - [ Directory Structure](#-directory-structure)
- [ Getting Started](#-getting-started)
  - [ Prerequisites](#-prerequisites)
  - [ Installation](#-installation)
  - [ Usage](#-usage)
  - [ Testing](#-testing)
- [ Project Roadmap](#-project-roadmap)
- [ Contributing](#-contributing)
- [ License](#-license)
- [ Acknowledgments](#-acknowledgments)

---

## Overview

CodeFuse is a **Real-Time Interactive Coding Collaborator** that allows developers to write, edit, and debug code collaboratively in real time. It's designed to improve productivity, enhance teamwork, and provide a seamless collaborative coding experience.

---

## Features

- **Real-Time Collaboration**: Multiple developers can write and edit code simultaneously.
- **Syntax Highlighting**: Support for popular programming languages.
- **Integrated Chat**: In-app communication for real-time discussions.
- **Code Sharing**: Share live code sessions via secure links.
- **Version History**: Track changes and roll back to previous versions.
- **Seamless Integration**: Supports GitHub integration for project management.

---

## Project Structure

### Directory Structure

```plaintext
CodeFuse/
├── client/             # Frontend application (React.js)
│   ├── public/         # Static files
│   └── src/            # React components and pages
│       ├── components/ # Reusable UI components
│       ├── pages/      # Application pages
│       └── utils/      # Helper functions and utilities
├── server/             # Backend application (Node.js/Express)
│   ├── controllers/    # API route handlers
│   ├── models/         # Database models (MongoDB)
│   ├── routes/         # API routes
│   └── utils/          # Backend utilities
├── .env                # Environment variables
├── package.json        # Project dependencies and scripts
└── README.md           # Project documentation
```

---

## Getting Started

### Prerequisites

- **Node.js** (v14 or higher)
- **npm** (v6 or higher) or **yarn**
- **MongoDB** (running instance for backend database)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/adityaRaj369/CodeFuse.git
   cd CodeFuse
   ```

2. Install dependencies for both client and server:

   ```bash
   cd client
   npm install

   cd ../server
   npm install
   ```

3. Create a `.env` file in the `server` directory and add the following:

   ```env
   PORT=5000
   MONGO_URI=mongodb://localhost:27017/codefuse
   JWT_SECRET=your_secret_key
   ```

### Usage

1. Start the backend server:

   ```bash
   cd server
   npm start
   ```

2. Start the frontend application:

   ```bash
   cd client
   npm start
   ```

3. Open your browser and navigate to `http://localhost:3000`.

### Testing

Run tests for both the client and server:

```bash
cd client
npm test

cd ../server
npm test
```

---

## Project Roadmap

- **Phase 1:** Implement core collaboration features (real-time editing, chat, and syntax highlighting).
- **Phase 2:** Add authentication and authorization.
- **Phase 3:** Integrate with GitHub and add version control features.
- **Phase 4:** Deploy to a cloud platform (e.g., AWS, Azure).

---

## Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes and open a pull request.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- Inspired by tools like **Visual Studio Live Share** and **CodeSandbox**.
- Thanks to the open-source community for their support and contributions.

