# 🏀 Sports Shop Agent AI Assistant

<img width="960" height="465" alt="image" src="https://github.com/user-attachments/assets/bdec4ffd-eb38-4928-8303-a1887ecb8b9d" />

## 🧠 Introduction

Welcome to the **Sports Shop Agent AI Assistant** project!  
In this codelab, you'll build a next-generation **Agent AI** application powered by **ADK**, **MCP Toolbox**, and **AlloyDB**.

This intelligent assistant helps users with common sports shop tasks through natural language interaction.

---

Your Agent AI will be able to:

- 🔍 Search for sports products using **natural language queries**  
- 🏬 Find **nearby stores** to purchase recommended products  
- 🛒 **Place new orders**  
- 📦 **Check existing order statuses**  
- 🚚 **Update orders** with preferred delivery methods  

---

## 🚀 Getting Started

1. **Clone this repository**

   ```bash
   git clone https://github.com/<your-username>/sports-shop-agent-ai.git
   cd sports-shop-agent-ai
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Set up your environment**

   - Create a new **AlloyDB** instance on Google Cloud  
   - Configure **MCP Toolbox for Databases**  
   - Add your credentials to `.env` file:
     ```bash
     ALLOYDB_CONNECTION_STRING=<your-connection-string>
     GOOGLE_CLOUD_PROJECT=<your-project-id>
     ```

4. **Run the development server**

   ```bash
   npm run dev
   ```

5. **Open in your browser**

   ```
   http://localhost:3000
   ```

---

## 🧩 Project Structure

```
sports-shop-agent-ai/
├── src/
│   ├── agent/           # ADK Agent logic
│   ├── database/        # AlloyDB setup and schema
│   ├── mcp/             # MCP Toolbox integration
│   ├── ui/              # Frontend (optional)
│   └── tests/           # Test scripts
├── .env.example
├── package.json
├── README.md
└── LICENSE
```

---

## 🧪 Testing Your Agent

Use the built-in tools to test:

```bash
npm run test
```

You can also deploy and test your Agent in a **Google Cloud** environment for production-level validation.

---

## 🧠 Technologies Used

- Agent Development Kit (ADK)
- MCP Toolbox for Databases]
- Node.js / TypeScript**
- Google Cloud Platform (GCP)**

---
