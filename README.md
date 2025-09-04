<div align="center">

# Open Lovable

Chat with AI to build React apps instantly.

<img src="https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExbmZtaHFleGRsMTNlaWNydGdianI4NGQ4dHhyZjB0d2VkcjRyeXBucCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/ZFVLWMa6dVskQX0qu1/giphy.gif" alt="Open Lovable Demo" width="100%"/>

</div>

## Setup

1. **Clone & Install**
```bash
git clone https://github.com/somdipto/open-lovable.git
cd open-lovable
npm install
```

2. **Add `.env.local`**
```env
# Required
E2B_API_KEY=your_e2b_api_key  # Get from https://e2b.dev (Sandboxes)
FIRECRAWL_API_KEY=your_firecrawl_api_key  # Get from https://firecrawl.dev (Web scraping)

# AI Providers (need at least one)
GOOGLE_API_KEY=your_gemini_api_key  # Get from https://aistudio.google.com (Gemini 1.5 Pro/Flash)
ANTHROPIC_API_KEY=your_anthropic_api_key  # Get from https://console.anthropic.com (Claude)
OPENAI_API_KEY=your_openai_api_key  # Get from https://platform.openai.com (GPT-4/5)
GROQ_API_KEY=your_groq_api_key  # Get from https://console.groq.com (Fast inference)
OPENROUTER_API_KEY=your_openrouter_api_key  # Get from https://openrouter.ai (200+ models)
```

## Supported AI Models

### 🔥 **Google Gemini** (Recommended - Default)
- **Gemini 1.5 Pro** - Best balance of quality and speed
- **Gemini 1.5 Flash** - Ultra-fast responses

### 🧠 **OpenRouter** (200+ Models)
- **Claude 3.5 Sonnet** - Excellent for complex code
- **GPT-4o** - Latest OpenAI model  
- **Llama 3.1 405B** - Powerful open-source model
- **Qwen 2.5 72B** - High-quality coding model

### ⚡ **Groq** (Ultra-Fast)
- **Kimi K2 Instruct** - Recommended for speed

### 🤖 **Direct APIs**
- **Anthropic Claude** - Direct access
- **OpenAI GPT-5** - Latest reasoning model

3. **Run**
```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000)

## ✨ Features

- **🤖 Multiple AI Providers** - Choose from Google Gemini, Claude, GPT, Groq, or OpenRouter
- **⚡ Real-time Code Generation** - Stream responses as AI writes your app
- **🎯 Smart File Detection** - AI automatically finds and edits the right files
- **📦 Package Management** - Automatically installs required dependencies
- **🔄 Live Preview** - See changes instantly in the browser
- **🎨 Modern Stack** - React, Next.js, TypeScript, Tailwind CSS

## License

MIT