# Phase-2-React-Code-Challenge: Bot Battlr

Welcome to **Bot Battlr** — the ultimate galactic web app where you can build your own **Bot Army**!
This project was built using **React** and a **JSON Server backend** to simulate a full-stack application.

---

## live link
https://phase-2-code-challenge-sable.vercel.app/

# Screenshot
Home Page
![Home Page](./src/assets/screencapture-localhost-3001-2025-11-03-16_46_09.png)

## Project Overview

The app allows users to:

* Browse a collection of available bots.
* Enlist bots into their personal army.
* Release bots from service.
* Permanently delete bots from the database.

This project was designed to practice **React fundamentals**, including:

* Components and props
* State management
* Event handling
* Data fetching
* Conditional rendering

---

## Learning Goals

* Implement a mini web app using **React**.
* Practice **components**, **props**, **state**, **events**, and **data fetching**.
* Understand how to structure and organize a React project.
* Manage data flow between components.

## Structure

```
App.jsx
 ├── Header.jsx
 ├── MyBotArmy.jsx   ← displays enlisted bots
 └── BotCollection.jsx
        └── BotCard.jsx  ← displays single bot info
```

### Explanation

* **App.jsx** fetches data from the backend and holds the main state.
* **BotCollection.jsx** receives the `bots` prop and displays them in a grid.
* **BotCard.jsx** displays details for each bot and handles user interactions.
* **MyBotArmy.jsx** displays only the bots that the user has enlisted.

---

## Setup and Installation

### 1. Clone the Repository

```bash
git clone https://github.com/Hillary90/Phase-2-Code-Challenge.git

cd Phase-2-Code-Challenge/

```

### 2. Install Dependencies

```bash
npm install
```

### 3. Start the JSON Server

Make sure you have a `db.json` file in your project root.

Run this command in your terminal:

```bash
json-server --watch db.json 
```

Check that your server is running at:
 [http://localhost:3000/bots](http://localhost:3000/bots)

### 4. Start the React App

```bash
npm run dev
```

---

## Core Features

* **View All Bots** — See all available bots fetched from the server.
* **Add to Army** — Click a bot to enlist it into your personal army.
* **Release a Bot** — Click to remove a bot from your army.
* **Delete Permanently** — Delete a bot from both the backend and frontend.

---

## Author

**Hillary Tanui**

---

## License

This project is licensed under the **MIT License** — feel free to use and modify for learning purposes.