# 📧 AI Cold Email Generator

An AI-powered Cold Email Generator for IT Sales teams that creates personalized, high-converting outreach emails using Google's Gemini AI.

Users simply select the service they want to pitch, choose the target designation, enter prospect details, and the application generates a professional cold email in seconds.

---

## ✨ Features

- AI-generated personalized cold emails
- Multiple IT service categories
- Role-based email generation
- Customizable tone (Professional, Conversational, Direct, Consultative)
- Personalized using:
  - Name
  - Company
  - Designation
  - LinkedIn Profile
  - Additional Context
- One-click Copy Email
- Responsive UI
- Powered by Google Gemini AI

---

## 🛠 Tech Stack

- HTML
- CSS
- Vanilla JavaScript
- Netlify Functions
- Google Gemini API (AI Studio)

---

## 📁 Project Structure

```
.
├── cold-email-generator_1.html
└── netlify
    └── functions
        └── generate.js
```

---

## 🚀 Deployment

### 1. Clone the repository

```bash
git clone https://github.com/arnavair1/Teceze_Consultancy_Cold-email-Generator.git
```

---

### 2. Install Netlify CLI (Optional)

```bash
npm install -g netlify-cli
```

---

### 3. Create Environment Variable

Inside Netlify Dashboard:

```
Site Settings
→ Environment Variables
→ Add Variable
```

Variable Name

```
GEMINI_API_KEY
```

Value

```
YOUR_GOOGLE_AI_STUDIO_API_KEY
```

---

### 4. Deploy

Deploy the repository to Netlify.

The Netlify Function will automatically use your Gemini API key securely.

---

## 🔑 Getting a Gemini API Key

1. Visit Google AI Studio

https://aistudio.google.com/

2. Sign in

3. Click

```
Get API Key
```

4. Create a new API Key

5. Copy it into the Netlify Environment Variable:

```
GEMINI_API_KEY
```

---

## 💡 How It Works

1. Select an IT service.
2. Choose the target designation.
3. Enter prospect information.
4. Select the preferred email tone.
5. Click **Generate Cold Email**.
6. Gemini AI generates a personalized outreach email.

---

## 🔒 Security

The Gemini API key is **never exposed** to the browser.

All AI requests are securely routed through a Netlify Function using server-side environment variables.

---

## 📸 Screenshot

Add your project screenshot here.

```
assets/screenshot.png
```

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

Developed by **Arnav**
