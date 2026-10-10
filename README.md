# LISTGPT

<p align="center">
  <img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/message-circle.svg" width="56" height="56" alt="LISTGPT icon" />
</p>

<h3 align="center">AI Chat with a Hand-Drawn Interface</h3>

<p align="center">
  A ChatGPT-inspired AI chat interface with a unique hand-drawn visual style.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/AI-OpenRouter-6C5CE7?style=flat-square" alt="OpenRouter" />
</p>

---

## <img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/sparkles.svg" width="20" height="20" /> About

**LISTGPT** is an AI chat interface inspired by ChatGPT, featuring a distinctive hand-drawn design language.

The goal is to combine a familiar AI conversation experience with a creative visual identity, without turning the interface into a notebook or a drawing canvas.

## <img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/layers.svg" width="20" height="20" /> Features

- **AI conversations** — Chat with AI models through OpenRouter.
- **Chat history** — Save and reopen conversations using browser local storage.
- **Model configuration** — Configure the API key and select an available model.
- **Responsive interface** — Adapt the layout for desktop and mobile screens.
- **Hand-drawn aesthetic** — Sketch-inspired typography and visual details.
- **Code formatting** — Display code blocks inside AI responses.
- **Conversation management** — Create and switch between conversations.
- **Browser-based storage** — Keep local chat data between sessions.

## <img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/code-2.svg" width="20" height="20" /> Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Application structure |
| CSS3 | Styling, layout, and responsive design |
| JavaScript | Chat logic and interface interactions |
| OpenRouter API | AI model access |
| LocalStorage | Local conversation and settings storage |
| Google Fonts | Typography |

## <img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/folder-tree.svg" width="20" height="20" /> Project Structure

The current version is designed as a single-page web application.

```text
LISTGPT/
└── index.html
```

The HTML file contains the application's structure, styles, and JavaScript logic.

## <img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/play.svg" width="20" height="20" /> Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/LISTGPT.git
cd LISTGPT
```

Replace `YOUR_USERNAME/LISTGPT` with your actual GitHub repository path.

### 2. Run the application

Open `index.html` in your browser.

For local development, you can also use the VS Code Live Server extension.

### 3. Configure your AI model

1. Open LISTGPT.
2. Open the settings or API configuration panel.
3. Enter your OpenRouter API key.
4. Select a supported model.
5. Start a conversation.

## <img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/settings-2.svg" width="20" height="20" /> OpenRouter Configuration

LISTGPT uses OpenRouter to connect to supported AI models.

Website: https://openrouter.ai/

API documentation: https://openrouter.ai/docs

You need a valid API key and access to a model supported by your OpenRouter account.

**Security note:** The current browser-based implementation may store the API key in local storage and send requests directly from the browser. Do not use this approach for a production service with shared users. A production deployment should route AI requests through a backend and keep API credentials on the server.

## <img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/workflow.svg" width="20" height="20" /> How It Works

1. The user writes a message in the chat interface.
2. LISTGPT adds the message to the current conversation.
3. JavaScript sends the conversation to the configured OpenRouter model.
4. The model generates a response.
5. LISTGPT displays the response and saves the conversation locally.

Actual behavior depends on the configured model and the implementation in `index.html`.

## <img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/database.svg" width="20" height="20" /> Data Storage

LISTGPT uses the browser's `localStorage` for supported local data, such as conversation history and settings.

This means:

- Data can persist after refreshing the page.
- Data is tied to the current browser and origin.
- Clearing browser storage can remove saved conversations and settings.
- Local storage is not a replacement for secure server-side storage or account synchronization.

## <img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/palette.svg" width="20" height="20" /> Design Philosophy

LISTGPT aims to keep the usability of a modern AI chat application while giving it a recognizable hand-drawn identity.

The interface focuses on:

- A familiar chat layout.
- Clear message hierarchy.
- Hand-drawn typography and subtle sketch-inspired details.
- Minimal distractions.
- Responsive behavior across screen sizes.

The visual style should support the conversation, not compete with it.

## <img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/list-checks.svg" width="20" height="20" /> Roadmap

Potential improvements include:

- [ ] Markdown rendering for AI responses.
- [ ] Improved syntax highlighting for code.
- [ ] Export and import conversations.
- [ ] Better attachment handling.
- [ ] Backend proxy for secure API requests.
- [ ] User accounts and cloud-synced history.
- [ ] Improved accessibility and keyboard navigation.
- [ ] Expanded model configuration options.

## <img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/shield-check.svg" width="20" height="20" /> Security

- Never publish API keys in a public repository.
- Avoid committing personal credentials or configuration secrets.
- Remember that browser storage is accessible to JavaScript running on the same origin.
- Use a backend for production API requests and credential management.

## <img src="https://cdn.jsdelivr.net/npm/lucide-static@latest/icons/scale.svg" width="20" height="20" /> License

No license has been specified yet.

Add a `LICENSE` file to define how other developers may use, modify, and distribute this project.

---

<p align="center">
  <strong>LISTGPT</strong>
  <br />
  <sub>A different visual language for AI conversations.</sub>
</p>
