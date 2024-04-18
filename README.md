# Smart Project

This project template uses **[Smart Actions](https://github.com/PR-Pilot-AI/smart-actions)** to add agentic behavior to your Github project.
It comes with fully-customizable, no-code [Github workflows](https://docs.github.com/en/actions/using-workflows) out-of-the-box:

## Tools

Tools are workflows you can run manually to interact with your AI agent

| Tool | Description |
|------|-------------|
| [🚀 Quick Task](https://github.com/PR-Pilot-AI/smart-project-template/actions/workflows/quick_task.yaml) | A generic tool that passes on your instructions directly to the agent, who will execute your instructions using its **[agent capabilities](https://docs.pr-pilot.ai/capabilities.html)**. |
| [🛠️ Build Something](https://github.com/PR-Pilot-AI/smart-project-template/actions/workflows/build_something.yaml) | Instruct the AI agent to build something for you using its **[agent capabilities](https://docs.pr-pilot.ai/capabilities.html)**. |
| [🧙‍♂️ Generate Tool](https://github.com/PR-Pilot-AI/smart-project-template/actions/workflows/generate_tool.yaml) | Instruct the AI agent to generate a new tool for your project. |
| [🧙‍♂️ Generate Automation](https://github.com/PR-Pilot-AI/smart-project-template/actions/workflows/generate_automation.yaml) | Create a new automation that will run the AI agent automatically when certain events occur. |
| [🧙‍♂️ Workflow Wizard](https://github.com/PR-Pilot-AI/smart-project-template/actions/workflows/workflow_wizard.yaml) | Create new workflows tailored to your project using the workflow wizard. |

## Automations
Automations are workflows that run automatically when certain events occur

| Automation | Description |
|------------|-------------|
| [📝 Format and Label New Issues](https://github.com/PR-Pilot-AI/smart-project-template/actions/workflows/format_label_new_issues.yaml) | When a new issue is created, it will automatically be formatted and labeled according to your [instructions](.bot_instructions/issue_formatting.md). |
| [🔍 Instant Pull Request Review](https://github.com/PR-Pilot-AI/smart-project-template/actions/workflows/instant_pr_review.yaml) | When a new pull request is created, it will automatically be reviewed according to your [instructions](.bot_instructions/pr_reviews.md). |

## Setup
It's simple: