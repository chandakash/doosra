# Doosra

**Doosra** is a powerful platform providing fast and reliable cricket APIs, combined with AI-enabled prompt answering capabilities. Built with **NestJS** for the backend and **PostgreSQL** for data management, Doosra is designed to deliver seamless performance and intelligent cricket data processing.

## Features

- **Real-Time Cricket APIs**: Get up-to-date data on ongoing matches, player stats, team rankings, and more.
- **AI-Enabled Querying**: Ask cricket-related questions, and let our AI model provide insightful responses.
- **Match Details**: Retrieve live scores, commentary, and player stats.
- **Team & Player Info**: Access detailed statistics and profiles for teams and players.
- **Historical Data**: Explore past matches, seasons, and tournaments.
- **Flexible APIs**: Easy-to-use, RESTful APIs with detailed documentation for developers.

## Technology Stack

- **Backend Framework**: [NestJS](https://nestjs.com/) - A progressive Node.js framework for building efficient, reliable, and scalable server-side applications.
- **Database**: [PostgreSQL](https://www.postgresql.org/) - A powerful, open-source object-relational database.
- **AI Integration**: Uses **Machine Learning** models to provide intelligent and contextual responses for cricket-related queries.
- **TypeScript**: Type-safe development using TypeScript for both the backend and AI layers.
  
## Getting Started

### Prerequisites

To run this project, you will need:

- **Node.js** (v14 or higher)
- **PostgreSQL** (v12 or higher)
- **Nest CLI** (Optional, for development)

### Installation

1. Clone the repository:
```sh
git clone https://github.com/chandakash/doosra.git
```
2. Navigate to the project directory:
```bash
cd doosra
```
3. Set up the environment variables. Create a .env file in the root directory with the following values:
```bash
DATABASE_HOST=localhost
DATABASE_PORT=5432
DATABASE_USER=yourusername
DATABASE_PASSWORD=yourpassword
DATABASE_NAME=doosra

```
4. To start the development server
```bash
npm run start:dev
```
