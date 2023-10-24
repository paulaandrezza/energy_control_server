# Energy Control Server

Energy Control Server is a Node.js application that allows you to manage and track energy consumption. This server is built with Node.js, Prisma, and Express, and it provides a flexible and efficient solution for managing energy-related data.

## Features

- Real-time data tracking.
- Automatic restart using Nodemon during development.
- Database powered by Prisma with MySQL.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js and npm installed on your machine.
- MySQL database set up and accessible.
- Knowledge of setting up environment variables for configuration.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/paulaandrezza/energy-control-server.git
```

2. Change to the project directory:

```bash
cd energy-control-server
```

3. Install the required dependencies:

```bash
npm install
```

## Configuration

Configure your MySQL database connection by setting the DATABASE_URL environment variable in a .env file. Example:

```
DATABASE_URL="mysql://username:password@localhost:3306/energycontrol"
```

## Usage

To start the Energy Control Server, run the following command:

```bash
npm start
```

The server will be accessible at http://localhost:3000 by default.
