# Google Agent Development Kit

This project serves as a foundational implementation of the [Google Agent Development Kit (ADK)](https://ai.google.dev/adk), demonstrating the creation of a modular, autonomous AI agent.

## Overview

The repository contains a self-contained **Executive Assistant** agent built with Google ADK.

**Core Components:**
- **Agent Definition:** A Python-based agent configuration (`agent.py`) defining the model, system instruction, and capabilities.
- **Execution Script:** A simple runner to test the agent locally.
- **Dependencies:** A `requirements.txt` for setting up the Python environment.

## Setup

### Prerequisites
- Python 3.9+
- [Google AI Studio API Key](https://aistudio.google.com/app/apikey)

### Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd my_first_agent
   ```

2. Install dependencies:
   ```bash
   pip install google-genai google-adk
   ```

## Configuration

Set your API key as an environment variable:

```bash
export GOOGLE_GEMINI_API_KEY="[GCP_API_KEY]"
```

## Usage

### Running the Agent

Execute the agent with a test query:

```bash
python run_agent.py "Hello, who are you?"
```

### Expected Output
```
> Agent: personal_assistant
> Message: Hello! I am your Executive Assistant. I am here to help you manage your tasks and workflows efficiently. How can I assist you today?
```
