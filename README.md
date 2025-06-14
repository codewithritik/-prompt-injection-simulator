# OpenAI Chat Playground

A simple web application that allows you to interact with OpenAI's Chat API using different models and parameters.

## Prerequisites

- Node.js (v14 or higher)
- npm (Node Package Manager)
- OpenAI API Key

## Setup Steps

1. Clone the repository:
```bash
git clone <your-repository-url>
cd <repository-name>
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory and add your OpenAI API key:
```
OPENAI_API_KEY=your_api_key_here
```

4. Start the application:
```bash
node app.js
```

The application will be available at `http://localhost:3000`

## Features

- Support for different OpenAI models
- Customizable parameters:
  - Temperature
  - Max tokens
  - Presence penalty
  - Frequency penalty
- System and user prompts
- Real-time response display

## Dependencies

- express: Web framework
- ejs: Template engine
- body-parser: Request body parsing
- openai: OpenAI API client
- dotenv: Environment variable management

## Project Structure

- `app.js`: Main application file
- `views/`: Contains EJS templates
- `public/`: Static assets
- `.env`: Environment variables (create this file)

## Usage

1. Open your browser and navigate to `http://localhost:3000`
2. Select your desired OpenAI model
3. Enter your system prompt and user prompt
4. Adjust the parameters as needed
5. Click generate to get the response

## Note

Make sure to keep your OpenAI API key secure and never commit it to version control.

---

## 🚀 Features

### 🔧 Prompt & Model Controls

- **Model Selection**
  - Choose between `gpt-3.5-turbo` and `gpt-4`
- **System Prompt**
  - Set the model's behavior or tone (e.g., "You are a professional marketing copywriter")
- **User Prompt**
  - Main input to describe what you want (e.g., "Describe the iPhone 15")

### 🎛️ Parameter Tuning

- **Temperature**
  - Controls creativity.  
    `0.0 = predictable`, `1.0 = balanced`, `>1.0 = creative/risky`
- **Max Tokens**
  - Limits the length of the output text
- **Presence Penalty**
  - Discourages the model from repeating similar ideas or topics
- **Frequency Penalty**
  - Reduces repetition of exact words or phrases

### 📤 Output Display

- Results are shown with the exact parameters used
- Each run displays a well-formatted product description

---

## 🛠️ How to Run the Playground

### ✅ Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/) (v14 or higher)
- [npm](https://www.npmjs.com/)
- An [OpenAI API key](https://platform.openai.com/account/api-keys)

### 📦 Steps

#### 1. Clone or Create the Project

```bash
git clone https://github.com/your-username/prompt-playground.git
cd prompt-playground
"# -prompt-injection-simulator" 
"# -prompt-injection-simulator" 
