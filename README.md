# 🇮🇳 Citizen AI – Intelligent Citizen Engagement Chatbot

**Citizen AI** is a smart, AI-powered chatbot built using **IBM Watson Assistant** to help users interact with citizen services like Aadhaar, Voter ID, PAN card, and more. The chatbot uses **Natural Language Processing (NLP)** to understand user queries and provide instant, human-like responses.

This project includes a **React-based front-end** and is deployed live on **Netlify**, with the chatbot powered by **IBM Cloud**.

---

## 🌐 Live Demo

🎯 [Click here to use the chatbot live](https://web-chat.global.assistant.watson.appdomain.cloud/preview.html?backgroundImageURL=https%3A%2F%2Feu-de.assistant.watson.cloud.ibm.com%2Fpublic%2Fimages%2Fupx-5b8231fe-1139-4ef9-8b41-481151c85904%3A%3Aa9f8eda8-32df-4b81-9bf5-8a7e97bd7d16&integrationID=0b08c9b4-15d7-45f9-be9b-2892f6011d97&region=eu-de&serviceInstanceID=5b8231fe-1139-4ef9-8b41-481151c85904)  

---

## 📌 Features

- 🧠 Built using IBM Watson Assistant (NLP chatbot platform)
- 💬 Responds to government-related queries like:
  - How to apply for Aadhaar
  - How to apply for Voter ID
  - How to get PAN card
  - And more!
- 🌐 Hosted on IBM Cloud (free Lite plan)
- ⚛️ Front-end made using React
- 🚀 Deployed using Netlify
- 🧩 Easy to enhance with more Q&A or Watson Discovery

---

## 🛠️ Tech Stack

| Technology         | Role in Project                          |
|--------------------|-------------------------------------------|
| **IBM Watson Assistant** | AI chatbot that understands user questions |
| **IBM Cloud**       | Cloud platform to host Watson services    |
| **React.js**        | Front-end framework for the chatbot UI    |
| **Netlify**         | Deployment platform (free hosting)        |
| **Git & GitHub**    | Version control and project sharing       |

---

## 💡 How It Works

1. User opens the chatbot website.
2. A script loads Watson Assistant and renders the chat widget.
3. User types a question (e.g., "How to apply for voter ID?")
4. Watson Assistant uses **Natural Language Processing (NLP)** to detect intent.
5. A matching action is triggered and Watson replies accordingly.

---

## 🧠 IBM Watson Assistant Design

- **Assistant Type**: Standard
- **Actions Built**:
  - Aadhaar Application
  - Voter ID Process
  - PAN Card Help
  - General Queries
- **UI**: Integrated via Watson Assistant's Web Chat Script in `index.html`

---

## 🔧 How I Built This Project

1. **Created an IBM Cloud Account**
   - Region: `eu-de` 
   - Created Watson Assistant with Lite plan

2. **Trained the Chatbot**
   - Used IBM Watson Assistant to define questions and responses
   - Added Actions using visual flow builder

3. **Created a React Front-End**
   - Used `create-react-app` to set up UI
   - Embedded Watson Assistant script in `public/index.html`

4. **Built and Tested**
   - Ran `npm run build` to generate static site

5. **Deployed**
   - Uploaded to GitHub for version control
   - Dragged `/build` folder to Netlify to host online

---

## 📸 Screenshots
### 🟢 Homepage with Chatbot Integrated
![Chatbot Homepage](./assests/chatbot.png)

---

### 🗣️ Asking a Query (Example)
![User Asking Aadhaar Query](./assests/asking-query.png)

---

### ✅ Bot's Response Output
![Bot Response](./assests/output.png)

---

## 📈 Future Enhancements

- 🌍 Add multi-language support (Hindi, Telugu, etc.)
- 📄 Connect Watson Discovery to search inside documents (PDFs/webpages)
- 🤖 Integrate Hugging Face models for smarter responses
- 💬 Add dynamic answers using backend/database
- 📊 Create an admin dashboard for monitoring usage

---

## 🚀 How to Run This Locally (Developers)

```bash
# 1. Clone the repo
git clone https://github.com/your-username/citizen-ai-chatbot.git
cd citizen-ai-chatbot

# 2. Install dependencies
npm install

# 3. Start local server
npm start
