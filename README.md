# 🤖 SpringAI Learnings

A collection of hands-on Spring AI modules built with **Java** and **Spring Boot**, exploring how to integrate Large Language Models (LLMs) into real-world applications.

---

## 📁 Project Structure

```
SpringAI/
├── SpringAI/               # Core Spring AI setup & fundamentals
├── chatbot/                # Conversational chatbot implementation
├── 2LLMs/                  # Working with two LLMs simultaneously
├── Prompts/                # Prompt engineering examples
└── SpringDocumentation/    # AI-powered documentation assistant
```

---

## 🧩 Modules

### `SpringAI`
The foundational module. Sets up Spring AI with a chosen LLM provider and demonstrates basic chat model interactions using the `ChatClient` API.

### `chatbot`
A conversational chatbot built with Spring AI. Supports multi-turn dialogue using in-memory chat history, showcasing how to maintain context across user interactions.

### `2LLMs`
Demonstrates how to wire and use **two different LLM providers** within a single Spring Boot application — useful for comparing outputs or routing queries based on context.

### `Prompts`
Explores prompt engineering techniques with Spring AI, including prompt templates, parameterized prompts, and dynamic prompt construction.

### `SpringDocumentation`
An AI assistant that answers questions about Spring documentation — an example of Retrieval-Augmented Generation (RAG) or document-grounded Q&A.

---

## 🚀 Getting Started

### Prerequisites

- Java 17+
- Maven 3.8+
- An API key for your chosen LLM provider (e.g. OpenAI)

### Run a module

```bash
cd chatbot/chatbot
./mvnw spring-boot:run
```

Set your API key as an environment variable before running:

```bash
export SPRING_AI_OPENAI_API_KEY=your_api_key_here
```

---

## 🛠 Tech Stack

| Technology     | Role                          |
|----------------|-------------------------------|
| Java           | Primary language              |
| Spring Boot    | Application framework         |
| Spring AI      | LLM integration layer         |
| OpenAI / Ollama| LLM providers                 |
| Maven          | Build tool                    |

---

## 📄 License

This project is open source. Feel free to explore, fork, and build on it.

---

> Built with ☕ and curiosity about AI + Spring.
