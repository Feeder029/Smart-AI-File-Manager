# Smart File Organizer

A local file organization workflow built with **n8n** and **Ollama**.

It automatically detects new files, uses a local AI model to determine their primary purpose, and moves them into the appropriate category.

## Categories

* Career
* Finance
* School
* Projects
* Personal
* Documents
* Media
* Other

## Tech Stack

* **n8n** - Workflow automation
* **Ollama** - Local AI classification
* **llama3.2:3b** - Text classification
* **gemma3:4b** - Image classification

## Folder Structure

```text
C:\SmartFileOrganizer
├── Inbox
└── Organized
    ├── Career
    ├── Finance
    ├── School
    ├── Projects
    ├── Personal
    ├── Documents
    ├── Media
    └── Other
```

## Status

🚧 Work in progress

Currently supports automatic file detection, classification, folder creation, and file organization.
