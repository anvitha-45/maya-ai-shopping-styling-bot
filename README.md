# Maya: Multimodal AI Shopping & Styling Chatbot

A live, conversational Telegram chatbot engineered with an automated backend orchestration layer capable of routing incoming text messages and voice updates, processing speech-to-text layers, and scraping production eCommerce portals via dynamic tool function-calling.

## 🚀 Features
- **Multimodal Message Router:** Uses discrete conditional If blocks to parse incoming Telegram text or voice payloads natively.
- **Embedded Script Optimization:** Features custom inline Python code components to programmatically sanitize and transform binary voice streams (`.oga` to `.ogg`).
- **Whisper Speech Processing:** Configures multi-part form-data HTTP request bodies to stream audio data chunks securely into Groq's whisper-large-v3-turbo API model.
- **Web Scraping Function-Calling:** Bounds an optimized ScraperAPI tool onto an LLM reasoning block to pull web content assemblies asynchronously from Amazon India via specific CSS selectors.

## 🛠️ Tech Stack
- **Chat Interface API:** Telegram Bot API (Trigger & Send nodes)
- **Workflow Engine:** n8n Architecture Core
- **AI Core Reasoning:** Google Gemini Model
- **Speech Decoding:** Groq Cloud Console (Whisper API Framework)
- **Custom Backend Scripting:** Inline Python Engine
- **Web Data Extraction:** ScraperAPI (Proxy DOM Wrapper)
