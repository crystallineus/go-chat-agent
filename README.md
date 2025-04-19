# Go Chat Agent

A simple AI-powered chatbot built in Go using the OpenAI API.

## Features

- Uses OpenAI GPT-3.5 to respond to user prompts
- Loads API keys from a `.env` file
- Fast and lightweight (thanks to Go!)
- Easy to expand into a CLI or web-based agent

## 🛠️ Getting Started

### Prerequisites

- [Go](https://golang.org/dl/) 1.18+
- An OpenAI API key – get one [here](https://platform.openai.com/)

### Installation

1. Clone this repo:

   ```bash
   git clone https://github.com/your-username/go-chat-agent.git
   cd go-chat-agent
   ```

2. Create a .env file and add your OpenAI API key:

   ```env
   OPENAI_API_KEY=your-api-key-here
   ```

3. Install dependencies:

   ```bash
   go mod tidy
   ```

4. Run the app:
   ```bash
   go run main.go
   ```
