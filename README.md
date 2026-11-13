# 🤖 AI Browser Quiz Agent

An AI-powered browser automation agent built using **n8n, Google Gemini API, and Browser Use MCP**. This project explores how AI agents can interact with browser-based quiz webpages and automate multi-step browser workflows.

Instead of simply generating text-based answers, the agent uses browser automation capabilities to interact with webpages through an MCP-powered browser workflow.

## 🚀 Project Overview

The AI Browser Quiz Agent accepts a quiz webpage URL and uses an automation workflow to process the webpage with AI-assisted browser interaction.

The project combines workflow automation, large language models, and browser automation to explore practical applications of AI agents.

## ✨ Key Features

- **URL-Based Input:** Submit a quiz webpage URL to the workflow.
- **AI Integration:** Uses Google Gemini API for AI-powered processing.
- **Browser Automation:** Integrates Browser Use MCP for browser interaction.
- **Workflow Orchestration:** Uses n8n to connect different services and manage execution.
- **Multi-Step Processing:** Designed to handle browser-based tasks through an automated workflow.
- **Modular Architecture:** Individual components can be modified and extended.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| n8n | Workflow automation and orchestration |
| Google Gemini API | AI-powered reasoning and processing |
| Browser Use MCP | Browser interaction through MCP |
| Model Context Protocol (MCP) | Communication between AI and external tools |
| REST APIs | Service integration |

## ⚙️ Workflow Architecture

The workflow follows this general architecture:

1. **User Input:** User submits a quiz webpage URL.
2. **Workflow Trigger:** n8n receives the submitted URL.
3. **AI Processing:** Gemini is integrated into the agent workflow.
4. **Browser Interaction:** Browser Use MCP provides browser interaction capabilities.
5. **Task Execution:** The agent processes the webpage according to the configured workflow.
6. **Result Handling:** The workflow handles the execution result.

## 📸 Project Screenshots

Screenshots of the actual implementation will be added here.

| Workflow Overview | Browser Automation |
|---|---|
| Add `screenshots/workflow-overview.png` | Add `screenshots/browser-agent.png` |

| Gemini Integration | Execution Result |
|---|---|
| Add `screenshots/gemini-integration.png` | Add `screenshots/execution-result.png` |

## 🔧 Setup & Configuration

### Prerequisites

- An n8n instance (local or hosted)
- Google Gemini API key
- Browser Use MCP configured and accessible to your workflow
- A supported browser automation environment

### Installation

**1. Clone the repository**

```bash
git clone https://github.com/princekushwah140-coder/ai-browser-quiz-agent.git
```

**2. Open the project folder**

```bash
cd ai-browser-quiz-agent
```

**3. Import the workflow**

- Open your n8n instance.
- Navigate to Workflows.
- Select Import from File.
- Import the JSON file from the `workflow` folder.

**4. Configure credentials**

Configure your Gemini API credentials and Browser Use MCP connection in your own environment.

**5. Activate and test**

Run the workflow with a supported quiz webpage URL and verify the execution results.

## 🔐 Security & Privacy

- API keys and authentication tokens are not included in this repository.
- Configure credentials securely within your own n8n instance.
- Do not upload private browser sessions, cookies, or personal information.
- Always use websites you are authorized to access.

## 🎯 Learning Outcomes

Through this project, I explored:

- Building AI-powered automation workflows.
- Integrating LLMs with external tools.
- Understanding Model Context Protocol (MCP).
- Connecting browser automation with n8n.
- Designing multi-step AI agent workflows.
- Working with APIs and service integrations.

## 🔮 Future Improvements

- Support for additional webpage formats.
- Improved error handling and execution monitoring.
- More robust browser interaction.
- Better handling of multi-step workflows.
- Structured execution reports.

## 👨‍💻 Developer

**Prince Kushwaha**

Aspiring Software & Backend Developer | AI Automation & Workflow Integration

- GitHub: [@princekushwah140-coder](https://github.com/princekushwah140-coder)
- LinkedIn: [Connect with me](https://www.linkedin.com/in/prince-kushwaha-02ab1a392/)

---

⭐ If you find this project interesting, consider giving this repository a star!

*Built as a hands-on project to explore AI agents, browser automation, and workflow engineering.*
