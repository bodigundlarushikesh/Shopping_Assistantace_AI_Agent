# 🛒 AI-Powered Shopping Assistant

An intelligent shopping assistant built using **n8n, Google Gemini AI, Telegram Bot API, and ScraperAPI**. This project helps users search for products online through Telegram and receive AI-powered shopping recommendations based on their requirements and budget.

Instead of manually browsing multiple websites, users can simply send a message to the Telegram bot, and the AI assistant automatically searches for relevant product information, processes the results, and delivers recommendations.

---

## 🚀 Project Overview

The AI Shopping Assistant automates the online product discovery process.

Users can send queries such as:

- Find red shirts under ₹1,000.
- Show me shoes under ₹5,000.
- Find the best smartphones under ₹25,000.
- Suggest affordable laptops for students.
- Find products with good customer ratings.

The AI Agent understands the user's requirements, retrieves relevant information using ScraperAPI, and generates an organized response through Telegram.

---

## 🔄 Workflow Architecture

The project uses the following n8n workflow components:

1. **Telegram Trigger** – Receives shopping queries from users through Telegram.
2. **AI Agent** – Understands the user's shopping requirements and coordinates the workflow.
3. **Google Gemini Chat Model** – Provides AI-powered natural language understanding and generates recommendations.
4. **HTTP Request (ScraperAPI)** – Retrieves product information from online sources.
5. **Code in JavaScript** – Processes, organizes, and formats the retrieved product data.
6. **Telegram Send Message** – Automatically sends the final shopping recommendations to the user.

---

## ✨ Key Features

- AI-powered product discovery.
- Search products using natural language.
- Budget-based product searches.
- Product name and price extraction.
- Product ratings and links when available.
- AI-generated shopping recommendations.
- Automated web data retrieval.
- JavaScript-based response formatting.
- Telegram chatbot integration.
- Automated workflow execution using n8n.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| n8n | Workflow automation |
| Telegram Bot API | User interaction |
| Google Gemini AI | AI-powered assistance |
| ScraperAPI | Web data retrieval |
| JavaScript | Data processing |
| HTTP Request | API integration |

---

## ⚙️ How It Works

**Step 1:** The user sends a shopping request through Telegram.

**Step 2:** The Telegram Trigger receives the message and forwards it to the AI Agent.

**Step 3:** Google Gemini understands the shopping requirements and helps coordinate the search.

**Step 4:** The HTTP Request node uses ScraperAPI to retrieve relevant product information.

**Step 5:** The JavaScript Code node processes and formats the retrieved information.

**Step 6:** The Telegram node sends the final product recommendations directly to the user.

---

## 💬 Example Interaction

**User Request:**

Find red shirts under ₹1,000.

**AI Shopping Assistant Response:**

Here are some red shirts under ₹1,000:

**Product 1:** The Indian Garage Co. Men's Slim Fit Casual Shirt

- Price: ₹560
- Rating: 3.8
- Product Link: View

**Product 2:** The Indian Garage Co. Men's Checkered Casual Shirt

- Price: ₹577
- Rating: 4.1
- Product Link: View

**Product 3:** LookMark Men's Cotton Blend Shirt

- Price: ₹299
- Rating: 3.6
- Product Link: View

*Product availability, prices, and ratings may change.*

---

## 🔧 Setup Instructions

### Prerequisites

Before running the workflow, you need:

- An n8n account.
- A Telegram account and Telegram bot token.
- A Google Gemini API key.
- A ScraperAPI API key.

### Installation Steps

1. Clone or download this GitHub repository.
2. Open your n8n instance.
3. Import the provided workflow JSON file.
4. Configure your Telegram bot credentials.
5. Connect your Google Gemini API credentials.
6. Configure your ScraperAPI API key in the HTTP Request node.
7. Verify the JavaScript Code node configuration.
8. Activate the workflow.
9. Open your Telegram bot and start searching for products.

---

## 📁 Project Structure

```text
AI-Powered-Shopping-Assistant/
│
├── My workflow.json
├── README.md
└── screenshots/
    └── workflow.png
```

---

## 🎯 Project Objective

The main objective of this project is to simplify online shopping through artificial intelligence and workflow automation.

By combining AI-powered query understanding, automated web data retrieval, and Telegram integration, this project provides users with a convenient way to discover products based on their shopping requirements and budget.

---

## 🔮 Future Enhancements

- Compare prices across multiple shopping platforms.
- Add product category filters.
- Provide personalized product recommendations.
- Add price tracking and alerts.
- Include product availability checking.
- Create a web-based shopping dashboard.
- Add voice-based shopping queries.

---

## 👨‍💻 Developer

**Rushikesh Bodigundla**

AI | Workflow Automation | n8n | Google Gemini | JavaScript

---

## ⭐ Support

If you find this project useful, consider giving the repository a ⭐ Star on GitHub!

**Built with ❤️ using AI and n8n Automation.**
