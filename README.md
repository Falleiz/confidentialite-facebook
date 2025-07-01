# 🌐 Propal Automator - Générateur de propositions commerciales intelligentes

Ce projet permet d'automatiser la création de propositions commerciales personnalisées en combinant l'IA (LLM), Google Sheets, Google Docs et un workflow visuel via **n8n**.

## 🚀 Fonctionnalités

- 🔄 Lecture des données clients depuis Google Sheets
- ✨ Génération automatique de contenu personnalisé (via LLM)
- 🧾 Remplissage dynamique d’un Google Doc (modèle)
- 📤 Envoi par email (Gmail API)
- 🧩 Interface visuelle via [n8n](https://n8n.io)

## 📂 Structure du dépôt

📁 workflows/
└── commercial-proposal-workflow.json
📁 docs/
└── politique_confidentialite.html
📁 assets/
└── screenshot_workflow.png


## 🛠️ Prérequis

- [n8n](https://n8n.io/) installé (cloud ou self-hosted)
- Un compte Google avec accès aux APIs suivantes :
  - Google Sheets API
  - Google Docs API
  - Gmail API
- Un compte OpenAI ou Gemini pour le modèle LLM
- Un document modèle Google Docs
- Une feuille de calcul Google Sheets contenant les informations client


