# gemini-ai-agent-python-tools
# Gemini AI Agent with Python Tools 🤖

A Python-based AI Agent powered by Google's Gemini API. This project demonstrates how an AI Agent can understand user requests, select appropriate tools, execute Python functions, and generate responses.

## 🚀 Features

- Gemini API Integration
- Automatic Function Calling
- Manual Function Calling
- Multiple Tool Calling
- Tool Selection
- Calculator Tool
- Greeting Tool
- Weather Tool
- Tool Argument Validation
- Error Handling

## 🛠️ Tech Stack

- Python
- Google Gemini API
- Google Gen AI SDK
- Google Colab

## 🔧 Available Tools

### 1. Calculator Tool
Performs mathematical operations:
- Addition
- Subtraction
- Multiplication
- Division

### 2. Greeting Tool
Generates personalized greeting messages.

### 3. Weather Tool
Returns sample weather information for a specified city.

> Note: The Weather Tool currently provides sample/static information and does not use a live weather API.

## 🧠 How It Works

1. User provides a query.
2. Gemini analyzes the query.
3. The AI Agent selects the appropriate tool.
4. Python executes the selected function.
5. The tool result is sent back to Gemini.
6. Gemini generates the final response.

## 💻 Example

**User:**
Multiply 1000 and 50 using the calculator tool.

**AI Agent:**
The result is 50000.

## 📦 Installation & Setup

1. Open the notebook using Google Colab.
2. Install the Google Gen AI SDK:

```python
!pip install -q google-genai
```

3. Add your Gemini API key to Google Colab Secrets.
4. Set the secret name as `GEMINI_API_KEY`.
5. Run the notebook cells.
6. Start interacting with the AI Agent.

## 🔐 Security

- Never expose your Gemini API key.
- Do not upload API keys to GitHub.
- Store API keys securely using Google Colab Secrets.

## 📚 Learning Outcomes

Through this project, I learned:

- AI Agent fundamentals
- LLM Function Calling
- Automatic and Manual Tool Calling
- Python function integration with LLMs
- Tool selection and execution
- Basic input validation
- Error handling in AI Agents

## 📌 Project Status

Completed ✅

## 👨‍💻 Author

B.Tech Computer Science Engineering Student

**Built as part of my AI Agent learning journey.**
