---
sidebar_label: Connecting To A Provider
---

# Connecting Your First AI Provider

To get started, you'll need to connect Roo Code to an AI model provider. We recommend starting with one of these options, which all offer access to Anthropic's powerful **Claude 3.7 Sonnet** model:

1.  **OpenRouter (Recommended):** A platform that provides access to multiple AI models, including Claude 3.7 Sonnet. This is often the easiest option for getting started.

2.  **Anthropic:** Direct access to Claude models from Anthropic. Requires applying for API access, and may be rate limited depending on your tier.

Choose one of these options and follow the instructions below to obtain an API key.

## Getting Your API Key

### Option 1: Using an LLM router

LLM routers allow you to use multiple models via a single provider, simplifying cost and API key management.

#### OpenRouter

1.  **Go to the OpenRouter website:** [https://openrouter.ai/](https://openrouter.ai/)
2.  **Sign in** with your Google or GitHub account.
3.  **Get an API Key:** Go to the [keys page](https://openrouter.ai/keys) and create a key.  Copy the key.

#### Requesty

1.  **Go to the Requesty website:** [https://requesty.ai/](https://requesty.ai/)
2.  **Sign in** with your Google or email account
3.  **Get an API Key:** Go to the [API management page](https://app.requesty.ai/manage-api) and create a key.  **Important:** Copy the key immediately, as you won't be able to see it again.

### Option 2: Using an LLM provider directly

If you prefer to use a specific LLM provider directly, that is always an option.

#### Anthropic

1.  **Go to the Anthropic Console:** [https://console.anthropic.com/](https://console.anthropic.com/)
2.  **Sign up** for an account or log in.
3.  **Create an API Key:** Go to the API keys page (you may need to navigate through the dashboard) and create a new key.  **Important:** Copy the key immediately, as you won't be able to see it again.

#### OpenAI

1.  **Go to the OpenAI Console:** [https://platform.openai.com/](https://platform.openai.com/)
2.  **Sign up** for an account or log in.
3.  **Create an API Key:** Go to the API keys page (you may need to navigate through the dashboard) and create a new key.  **Important:** Copy the key immediately, as you won't be able to see it again.

## Configuring Roo Code in VS Code

1.  **Open the Roo Code Sidebar:** Click the Roo Code icon (<Codicon name="rocket" />) in the VS Code Activity Bar.  You should see the welcome screen.

2.  **Select your API Provider:** In the "API Provider" dropdown, choose your API provider.

3.  **Enter your API Key:** Paste your API key into the "API Key" field.

4. **Select your Model:**
    * If you're using **OpenRouter**, select `anthropic/claude-3.7-sonnet`.
    * If you're using **Anthropic**, select `claude-3-7-sonnet-20250219`.

5.  **Click "Let's go!":**  Roo Code will save your settings, and you'll be ready to start coding!
