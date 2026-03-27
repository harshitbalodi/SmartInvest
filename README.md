# My Fullstack App

## Overview
This project is a fullstack application that consists of a backend built with Python and a frontend built with React. The backend handles API requests and data management, while the frontend provides a user interface for interacting with the application.

## Project Setup

### Prerequisites
- **Python** 3.12+
- **Node.js** (LTS recommended)
- **npm**

### Backend

1. Navigate to the server directory:
   ```bash
   cd server
   ```
2. Create a virtual environment:
   ```bash
   # macOS / Linux
   python3 -m venv .venv

   # Windows
   python -m venv .venv
   ```
3. Activate the virtual environment:
   ```bash
   # macOS / Linux
   source .venv/bin/activate

   # Windows (Command Prompt)
   .venv\Scripts\activate.bat

   # Windows (PowerShell)
   .venv\Scripts\Activate.ps1
   ```
4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Frontend

1. Navigate to the client directory:
   ```bash
   cd client
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```

## Project Structure
```
my-fullstack-app
├── backend
│   ├── src
│   ├── tests
│   ├── requirements.txt
│   └── .env.example
├── frontend
│   ├── src
│   ├── package.json
│   └── vite.config.js
├── docs
│   ├── reference.txt
│   └── figma-design-notes.txt
├── .gitignore
└── README.md
```

## Backend
- **Entry Point**: `backend/src/main.py`
- **Configuration**: `backend/src/config.py`
- **Controllers**: `backend/src/controllers/api_controller.py`
- **Models**: `backend/src/models/base_model.py`
- **Routes**: `backend/src/routes/api_routes.py`
- **Services**: `backend/src/services/base_service.py`
- **Utilities**: `backend/src/utils/helpers.py`
- **Tests**: `backend/tests/test_main.py`
- **Dependencies**: Listed in `backend/requirements.txt`

## Frontend
- **Main Component**: `frontend/src/App.jsx`
- **Pages**: `frontend/src/pages/Home.jsx`, `frontend/src/pages/Dashboard.jsx`
- **Components**: `frontend/src/components/Button.jsx`, `frontend/src/components/Card.jsx`, `frontend/src/components/Header.jsx`, `frontend/src/components/Layout.jsx`
- **Styles**: `frontend/src/styles/global.css`
- **Build Tool**: Configured in `frontend/vite.config.js`
- **Dependencies**: Listed in `frontend/package.json`

## Documentation
- **Reference**: `docs/reference.txt` contains notes or documentation relevant to the project.
- **Figma Design Notes**: `docs/figma-design-notes.txt` contains notes and specifications for the Figma design components.

## Getting Started
1. Clone the repository.
2. Navigate to the backend directory and install dependencies using `pip install -r requirements.txt`.
3. Set up environment variables as needed in the `.env` file.
4. Run the backend server.
5. Navigate to the frontend directory and install dependencies using `npm install`.
6. Start the frontend application.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.