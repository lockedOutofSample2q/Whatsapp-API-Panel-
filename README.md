# 📲 WA Panel — WhatsApp API Management Panel

> The WhatsApp API management panel Meta forgot to build.

> Vibe coded with [OpenClaw](https://openclaw.ai) & Claude. ✨

**WA Panel** is a fully open-source, self-hosted **WhatsApp API panel** for the **official WhatsApp Business API** — giving businesses a complete, polished interface to manage their WhatsApp API integration without duct-taping together a dozen third-party tools.

Whether you're looking for a **Meta API dashboard**, a **WhatsApp Business API panel**, or a self-hosted alternative to expensive SaaS platforms, WA Panel has you covered.

---

## ✨ Features

### 🏠 Dashboard
A real-time command center for your **WhatsApp API** operations. Monitor message volume, conversation health, campaign performance, and system status at a glance.

### 📊 Analytics
Deep insights into WhatsApp API message delivery, open rates, response times, and campaign ROI. Know exactly what's working and why.

### 💬 Chats
A full WhatsApp Web–style inbox with everything you'd expect: conversation threads, media support, read receipts, and **labels** to organize contacts and conversations your way. Broadcast lists built right in.

### 👥 Contacts
A clean CRM-lite contacts tab to manage your WhatsApp audience — import, segment, tag, and keep everything structured.

### 📣 Campaign Builder
An **Instantly-style** campaign builder for the **WhatsApp Business API**. Design, schedule, and launch bulk messaging campaigns to segmented audiences with a few clicks — no developer required.

### 🔁 Flow Builder
An **n8n-style** visual flow builder for creating sophisticated **WhatsApp API automation** workflows. Drag, connect, and deploy multi-step messaging logic without writing a single line of code.

### 🤖 AI Autoresponder
Powered by **OpenRouter**, giving you access to any leading AI model for smart, context-aware automatic replies over the **WhatsApp API**. Set it up once, and let it handle the inbox intelligently.

### 📋 Templates
Manage your **WhatsApp Business API** message templates end-to-end — submit new templates for Meta approval, track their status, and deploy approved ones directly into campaigns or flows.

### 🏢 Business Profile Management
Edit and manage your **WhatsApp Business** profile — display name, description, address, website, category, and more — all from one place via the **Meta API**.

---

## 🚀 Getting Started

### Prerequisites

- Node.js 18+
- A verified **WhatsApp Business API** account (Meta Cloud API or on-premise)
- OpenRouter API key (for AI autoresponder)

### Installation
```bash
git clone https://github.com/yourname/wa-panel.git
cd wa-panel
cp .env.example .env
npm install
npm run dev
```

Configure your environment variables in `.env`:
```env
WHATSAPP_ACCESS_TOKEN=your_meta_api_token
WHATSAPP_PHONE_NUMBER_ID=your_phone_number_id
OPENROUTER_API_KEY=your_openrouter_key
DATABASE_URL=your_db_connection_string
```

### Running in Production
```bash
npm run build
npm start
```

---

## 🤝 Contributing

Contributions are welcome and encouraged.

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add your feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

Please follow the existing code style and include tests where applicable. For major changes, open an issue first to discuss what you'd like to change.

---

## 🔍 Keywords

`whatsapp-api` `whatsapp-api-panel` `whatsapp-business-api` `meta-api` `whatsapp-dashboard` `whatsapp-automation` `whatsapp-campaign` `whatsapp-flow-builder` `whatsapp-autoresponder` `whatsapp-crm` `meta-cloud-api` `whatsapp-management-panel`

---

## 📄 License

idk about it, I'll say it is opensource

---

## ⚠️ Disclaimer

WA Panel is an independent open-source project and is not affiliated with, endorsed by, or associated with Meta Platforms, Inc. or WhatsApp. Use of the WhatsApp Business API is subject to [Meta's Terms of Service](https://www.whatsapp.com/legal/business-terms).
