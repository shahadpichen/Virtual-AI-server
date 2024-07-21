# AI Avatar Server

This is the backend server for the AI Avatar project. It is built using Node.js and Express, and it handles various endpoints for interacting with the AI Avatar application.

## Features

- Chat functionality using AI
- Integration with Eleven Labs for text-to-speech
- Cross-Origin Resource Sharing (CORS) enabled for frontend communication
- JSON body parsing using body-parser

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Node.js (v14.x or higher)
- npm (v6.x or higher)

### Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/ai-avatar-server.git
cd ai-avatar-server
```
 2. Install the dependencies:
    
```bash
npm install
```

3.Create a .env file in the root directory and add your environment variables. Here is an example:

```bash
PORT=5000
ELEVEN_LABS_API_KEY=your-eleven-labs-api-key
```
Running the Server
To start the server, run the following command:

```bash
npm start
```
