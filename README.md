
# ☁️ Cloud Support Chatbot — Google Cloud Dialogflow

![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)
![Dialogflow](https://img.shields.io/badge/Dialogflow-FF9800?style=for-the-badge&logo=dialogflow&logoColor=white)
![NLP](https://img.shields.io/badge/NLP-Natural_Language_Processing-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

---

## 📌 Project Overview

A **cloud-based conversational AI chatbot** built using **Google Cloud Dialogflow Essentials** that can intelligently answer queries related to cloud computing concepts, services, and technologies.

The chatbot uses **Natural Language Understanding (NLU)** to match user queries to the correct intent and respond with accurate, informative answers — even when users type abbreviations like `k8s` (Kubernetes) or `vm` (Virtual Machine).

---

## 🚀 Platform

> Agent Name: `cloud-support-bot`  
> Platform: [dialogflow.cloud.google.com](https://dialogflow.cloud.google.com)

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **Google Cloud Platform (GCP)** | Cloud infrastructure |
| **Dialogflow Essentials** | NLU-based chatbot engine |
| **Natural Language Processing** | Understanding user queries |
| **Machine Learning (ML)** | Intent recognition & training |
| **REST API** | Backend communication |

---

## ✨ Features

- ✅ **15 trained cloud computing intents** covering key topics
- ✅ Handles **abbreviations** — `k8s`, `vm`, `aws` etc.
- ✅ Built entirely on **Google Cloud** (free tier)
- ✅ Real-time responses via **Dialogflow test console**
- ✅ Easily extendable with **webhooks & Cloud Functions**
- ✅ Can be deployed on **Slack, WhatsApp, Google Assistant**

---

## 💬 Supported Queries (15 Intents)

| # | Topic | Example Query |
|---|-------|--------------|
| 1 | Cloud Computing | "What is cloud computing?" |
| 2 | Google Cloud | "What is GCP?" |
| 3 | Virtual Machine | "What is a VM?" |
| 4 | Cloud Storage | "What is cloud storage?" |
| 5 | Scalability | "What is scalability?" |
| 6 | AWS | "What is AWS?" |
| 7 | Microsoft Azure | "What is Azure?" |
| 8 | Load Balancing | "What is load balancing?" |
| 9 | Containerization | "What is Docker?" |
| 10 | Kubernetes | "What is k8s?" |
| 11 | Serverless Computing | "What is serverless?" |
| 12 | DevOps | "What is DevOps?" |
| 13 | Cloud Security | "What is cloud security?" |
| 14 | SaaS | "What is SaaS?" |
| 15 | Cloud Migration | "What is cloud migration?" |

---

## 📸 Screenshots

### Agent Intents Dashboard
![Intents Dashboard](https://raw.githubusercontent.com/Chandrashekhar-cloud/Cloud-Support-Chatbot-Dialogflow/main/screenshots/intents_dashboard.png)

### Sample Conversation — Cloud Computing
![Cloud Computing](https://raw.githubusercontent.com/Chandrashekhar-cloud/Cloud-Support-Chatbot-Dialogflow/main/screenshots/conversation_cloud_computing.png)

### Sample Conversation — Kubernetes (k8s)
![Kubernetes](https://raw.githubusercontent.com/Chandrashekhar-cloud/Cloud-Support-Chatbot-Dialogflow/main/screenshots/conversation_kubernetes.png)

### Sample Conversation — Virtual Machine (vm)
![Virtual Machine](https://raw.githubusercontent.com/Chandrashekhar-cloud/Cloud-Support-Chatbot-Dialogflow/main/screenshots/conversation_vm.png)

---

## 🏗️ How It Works

```
User types query
      ↓
Dialogflow NLU Engine processes input
      ↓
ML model matches to closest Intent
      ↓
Bot returns configured response
```

1. **User** types a cloud-related question in natural language
2. **Dialogflow** processes the input using its NLU engine
3. The **ML model** matches the query to the best-fit intent
4. The **bot responds** with a clear, accurate answer

---

## 🔧 Setup & Replication

1. Go to [dialogflow.cloud.google.com](https://dialogflow.cloud.google.com)
2. Sign in with your Google account
3. Click **"Create Agent"** → Name it `cloud-support-bot`
4. Click **"Create Intent"** for each of the 15 topics above
5. Add **3 training phrases** per intent
6. Add a **response** for each intent
7. Test using the **"Try it now"** console on the right panel

---

## 🔮 Future Enhancements

- [ ] Deploy on **Slack** for DevOps team integration
- [ ] Connect to **Google Cloud Functions** via webhooks
- [ ] Add **live GCP service status** via API integration
- [ ] Upgrade to **Dialogflow CX** for complex flows
- [ ] Integrate **Vertex AI (Gemini)** for dynamic responses
- [ ] Add **analytics dashboard** with BigQuery + Data Studio

---

## 📄 Report

Full implementation report available in [`Cloud_Chatbot_Report.pdf`](Cloud_Chatbot_Report.pdf)

---

## 📚 References

- [Google Cloud Dialogflow Documentation](https://cloud.google.com/dialogflow/es/docs)
- [Google Cloud Platform Overview](https://cloud.google.com/docs/overview)
- [Kubernetes Documentation](https://kubernetes.io/docs/)
- [Docker Documentation](https://docs.docker.com/)

---

⭐ **If you found this useful, give it a star!**

