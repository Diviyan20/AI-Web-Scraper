
# AI Web Scraper 🕵️‍♂️🤖
An AI-powered web scraper that fetches, parses, and analyzes website landing pages using Python, BeautifulSoup, and OpenAI GPT models. Built with Gradio for an intuitive interface, this tool generates summaries, insights, and structured content from any company website.

# 🚀 Features

- 🌐 **Smart Web Scraping** – Extracts website content and cleans up irrelevant scripts, styles, and metadata.

- 🧠 **AI-Powered Summaries** – Uses OpenAI GPT to analyze content and generate human-like summaries.

- 🗂 **Structured Data Extraction** – Extracts company details like name, description, services, and contact info.

- 🧩 **Gradio Web UI** – Simple, interactive interface for non-technical users.

- ⚡ **Streaming GPT Responses** – Displays live AI responses in real-time.

🔧 **Error Handling** – Gracefully handles invalid URLs, missing pages, and network failures.

🛠 **Easy to Extend** – Ready for enhancements like multi-page crawling, RAG, and chatbot capabilities.

# 🧠 How It Works

1. **Enter a Website URL** → Provide the landing page link.

2. **Scraping & Cleaning** → Uses BeautifulSoup to fetch and clean website content.
3. **LLM Analysis** → Sends content to GPT-4o-mini for summarization and insights.

4. **Streaming Output** → The AI’s response streams in real-time on the Gradio interface.

# 🛠️ Tech Stack

| Component          | Technology                                     |
| ------------------ | ---------------------------------------------- |
| **Frontend**       | [Gradio](https://gradio.app)                   |
| **Backend**        | Python 3.10+                                   |
| **AI Models**      | OpenAI GPT (`gpt-4o-mini`)                     |
| **Scraping**       | Requests + BeautifulSoup                       |
| **Env Management** | Python-dotenv                                  |
| **Deployment**     | Hugging Face / Streamlit / Docker *(optional)* |

# 📸 Demo

[View the Demo here](https://1drv.ms/v/c/baa26b84f8ba2114/EW6AK5Uu2OBGlh4Hhkr-e-cBj2RL4UGvrVKeGzkDZKs1ZA?e=N196fM)


# 📦 Installation

1. Clone the Repository

`git clone https://github.com/Diviyan20/AI-Web-Scraper`


2. Install Jupyter -> [Jupyter](https://jupyter.org/install)

3. Open Jupyter Notebook

   <img width="1865" height="743" alt="image" src="https://github.com/user-attachments/assets/acba7d2c-d2a4-4a73-8331-d7c19d8d2631" />


   
5. Locate your file
   <img width="1572" height="170" alt="image" src="https://github.com/user-attachments/assets/0d3933af-ae52-4751-8e93-cc84dff4696a" />

6. Add Environment Variables

`OPENAI_API_KEY= your_openai_api_key`

# ▶️ Usage

## Run the App

`Shift + Enter in your Jupyter Notebook`

This will launch a Gradio web interface at:

`http://127.0.0.1:7860`




