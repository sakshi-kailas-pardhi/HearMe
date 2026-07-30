# 🛡️ HearMe – AI-Powered Personal Safety System

> An AI-powered personal safety application that analyzes emergency voice input, assesses risk using Azure AI services, and helps users quickly notify trusted contacts through WhatsApp or SMS during distress situations.

[![React](https://img.shields.io/badge/React-19-blue?logo=react)]()
[![Vite](https://img.shields.io/badge/Vite-Frontend-purple?logo=vite)]()
[![Azure AI Speech](https://img.shields.io/badge/Azure-AI%20Speech-0078D4?logo=microsoftazure)]()
[![Azure AI Language](https://img.shields.io/badge/Azure-AI%20Language-0078D4?logo=microsoftazure)]()
[![Firebase](https://img.shields.io/badge/Firebase-Storage-FFCA28?logo=firebase)]()
[![Netlify](https://img.shields.io/badge/Netlify-Deployed-00C7B7?logo=netlify)]()

🌐 **Live Demo:** https://candid-concha-94703b.netlify.app/

💻 **GitHub Repository:** https://github.com/sakshi-kailas-pardhi/HearMe

## 📌 Problem

During emergency situations, people often struggle to communicate their condition, describe their location, or contact trusted people quickly. Valuable time can be lost while deciding what action to take.

## 💡 Solution

HearMe simplifies emergency response through a single emergency action.

After the user presses the **Emergency** button, the application:

- Captures the user's location and emergency time
- Records the user's voice
- Converts speech into text using Azure AI Speech
- Performs sentiment analysis and key phrase extraction using Azure AI Language
- Estimates the level of risk using a rule-based risk engine
- Generates a pre-filled emergency alert
- Allows the user to quickly notify trusted contacts through WhatsApp or SMS

  ## ✨ Features

- 🎤 Voice-based emergency reporting
- 📍 Automatic location capture
- 🧠 AI-powered speech-to-text conversion
- 😊 Sentiment analysis
- 🔑 Key phrase extraction
- 🚨 Rule-based risk assessment (LOW / MEDIUM / HIGH)
- 📱 One-click WhatsApp emergency alert
- 💬 One-click SMS emergency alert
- 🌐 Browser-based deployment using Netlify

  ## 🏗️ System Architecture

```mermaid
flowchart TD

A[Emergency Button Pressed]
-->B[Capture Location & Time]

B-->C[Record Voice]

C-->D[Azure AI Speech]

D-->E[Speech to Text]

E-->F[Azure AI Language]

F-->G[Sentiment Analysis]

F-->H[Key Phrase Extraction]

G-->I[Risk Evaluation]

H-->I

I-->J[LOW / MEDIUM / HIGH]

J-->K[Generate Alert]

K-->L[WhatsApp]

K-->M[SMS]
```
