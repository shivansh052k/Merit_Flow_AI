# Merit Flow: The Culture & Ethical Orchestrator 🚀
> **Hackathon Entry:** IBM Dev Day AI Demystified 2026
> **Theme:** AI Demystified - From Idea to Deployment
> **Team** Team-Semantic-Snipers-IBM-Dev-Day-AI-Hackathon-2026
## 🎯 The Vision
**Merit Flow** is an agentic AI solution that fosters a transparent, healthy, and productive work environment. Instead of using AI for surveillance, we use it for **enablement**.

We bridge the gap between "doing work" and "being recognized" by orchestrating the flow of merit across the organization.

## ⚠️ The Problem
* **The Recognition Gap:** Hard work often goes unnoticed in remote/hybrid setups.
* **Stagnant Growth:** Employees have access to course libraries (Coursera/edX) but lack the *context* on what to learn and when.
* **Delayed Feedback:** Annual surveys are too slow to catch burnout or toxic culture trends.

## 💡 The Solution
Merit Flow operates as an intelligent layer inside **IBM watsonx Orchestrate**, connecting your communication tools (Slack/Teams) with HR systems and Learning Platforms.

### 1. Recognition Engine 🏆
* **What it does:** Automates "Kudos" and rewards.
* **How:** When a project is marked "Complete" in the system, the Agent triggers a workflow to prompt the manager or peers for recognition, logging it directly to the employee's merit profile.

### 2. Growth Pathfinder 🧭
* **What it does:** Context-aware education recommendations.
* **How:** The Agent analyzes recent project logs. If an employee struggles with a specific task (e.g., "API Integration"), the Agent queries **watsonx.ai** to recommend a specific, bite-sized course module to bridge that gap immediately.

### 3. Culture Pulse ❤️
* **What it does:** Ethical sentiment tracking.
* **How:** Instead of spying on messages, the Agent conducts anonymous "Pulse Checks." It uses **Granite models** to aggregate sentiment data and report "Culture Health" to leadership without exposing individual identities.

## 🛠️ Tech Stack
* **Core Platform:** [IBM watsonx Orchestrate](https://www.ibm.com/products/watsonx-orchestrate) - Managing the agent workflow and tool connections.
* **Intelligence:** [IBM watsonx.ai](https://www.ibm.com/products/watsonx-ai) - Powering the sentiment analysis and recommendation logic using **Granite-3-8b-instruct**.
* **Integration:** Custom **OpenAPI** skills connecting to a mock HR Data backend.

## 🚀 Getting Started (Dev)
To run this project locally for development:

1.  **Clone the repo:**
    ```bash
    git clone [https://github.com/JayR1031/merit-flow.git](https://github.com/JayR1031/merit-flow.git)
    ```
2.  **Mock Data Setup:**
    Load the `data/mock_employees.csv` into your local testing environment.
3.  **API Spec:**
    Import `openapi/merit-flow-api.yaml` into your watsonx Orchestrate "Custom Skills" panel.

## 👥 The Team
* **Architect:** @JayR1031
* **Agent Engineer:** @Gustavo-Rubio
* **Tools & Integrations:** @munachimso-victor
* **AI & Prompts:** @shivansh052k
* **Frontend & Data:** @sadaa.kakarla

---
*Built with ❤️ for the IBM Dev Day Hackathon 2026.*
