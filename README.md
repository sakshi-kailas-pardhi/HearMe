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

## 🛠️ Tech Stack

| Category | Technologies |
|----------|--------------|
| Frontend | React, Vite |
| AI Services | Azure AI Speech, Azure AI Language |
| Cloud | Firebase, Netlify |
| APIs | REST APIs |
| Language | JavaScript |

## 🖥️ Project Previews

<table width="100%">
  <tr>
    <td width="50%" align="center">
      <b>🏠 Homepage</b><br><br>
      <img src="https://github.com/user-attachments/assets/4604ba39-b8ec-4479-ad87-8b06b97b2be5" alt="Homepage Layout" width="100%">
    </td>
    <td width="50%" align="center">
      <b>🤖 AI Analysis</b><br><br>
      <img src="https://github.com/user-attachments/assets/d3546c15-b004-4975-857f-b608ecd56f61" alt="AI Analysis Panel" width="100%">
    </td>
  </tr>
  <tr>
    <td width="50%" align="center">
      <b>⚠️ Risk Assessment</b><br><br>
      <img src="https://github.com/user-attachments/assets/2ba1e618-62f3-46ca-bcc0-7dbb990d43e1" alt="Risk Assessment Metrics" width="100%">
    </td>
    <td width="50%" align="center">
      <!-- Leave this cell empty or put a brief project description/stats here to balance the 2x2 grid -->
      <b>✨ Key Features</b><br>
      <ul align="left">
        <li>Real-time automated risk evaluation</li>
        <li>Intelligent AI-driven data analysis</li>
        <li>Clean, responsive user interface</li>
      </ul>
    </td>
  </tr>
</table>

---

## 🏗️ System Architecture

<p align="center">
  <img src="https://github.com/user-attachments/assets/bda7f343-dfea-4952-9a30-da420a2a84f0" alt="Architecture Diagram" width="65%">
</p>





