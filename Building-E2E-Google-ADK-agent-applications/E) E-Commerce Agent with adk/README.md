# 🏀 Sports Shop Agent AI Assistant

![Sports Shop Agent AI](7d9b5c1b10d1c654.png)

## 🧠 Introduction

Welcome to the **Sports Shop Agent AI Assistant** project!  
In this codelab, you'll build a next-generation **Agent AI** application powered by **ADK**, **MCP Toolbox**, and **AlloyDB**.

This intelligent assistant helps users with common sports shop tasks through natural language interaction.

---

## ⚙️ What You'll Build

Your Agent AI will be able to:

- 🔍 Search for sports products using **natural language queries**  
- 🏬 Find **nearby stores** to purchase recommended products  
- 🛒 **Place new orders**  
- 📦 **Check existing order statuses**  
- 🚚 **Update orders** with preferred delivery methods  

---

## 🎯 What You'll Learn

In this codelab, you’ll gain hands-on experience with:

1. **Provisioning and populating** an **AlloyDB for PostgreSQL** database  
2. Setting up **MCP Toolbox for Databases** with your AlloyDB instance  
3. Designing and developing an **AI Agent** using the **Agent Development Kit (ADK)**  
4. **Testing** your Agent and MCP Toolbox in a **cloud environment**  
5. Leveraging **AlloyDB’s advanced query capabilities** for intelligent, contextual agent responses  

---

## 🧰 What You'll Need

Before you start, ensure you have:

- ✅ A **Chrome web browser**  
- ✅ A **Gmail account**  
- ✅ A **Google Cloud Project** with **billing enabled**

This codelab is suitable for developers of **all levels**, including **beginners**.

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

- **[Agent Development Kit (ADK)](https://developers.google.com/agent-dev-kit)**
- **[MCP Toolbox for Databases](https://cloud.google.com/mcp-toolbox)**
- **[AlloyDB for PostgreSQL](https://cloud.google.com/alloydb)**
- **Node.js / TypeScript**
- **Google Cloud Platform (GCP)**

---

## 📄 License

This project is licensed under the **Apache 2.0 License** – see the [LICENSE](LICENSE) file for details.

---

## ❤️ Acknowledgments

- Google Cloud Codelabs Team  
- AlloyDB Engineering Group  
- ADK Developer Community  

---

> “Empower your applications with intelligent, context-aware agents — one query at a time.”  
> — *Sports Shop Agent AI Team*
