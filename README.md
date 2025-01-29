# Spectrum Blog

Welcome to the **Spectrum Blog** project! This is a blog application built with a simple front-end and back-end architecture. The project uses **JSON Server** to simulate a backend without needing an actual database.

## Prerequisites

Before you begin, ensure you have the following software installed on your machine:

- [Node.js](https://nodejs.org/) (to run the front-end)
- **npm** (comes with Node.js)

## Project Setup

### Frontend Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/Luke-356/Spectrum-Blog
   ```
   ```bash
   cd Spectrum-Blog

2. Install front-end dependencies:

   ```bash
   npm install

3. Run the front-end application:

   ```bash
   npm start

### Backend Setup

1. Navigate to the data directory:
   ```bash
   cd data

2. Start JSON Server to simulate a backend:
   ```bash
   json-server --watch db.json --port 8000

This will start the backend server at http://localhost:8000. 
