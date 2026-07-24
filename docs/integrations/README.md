# Integrations

## Overview

The Java Mentor AI Agent integrates Cursor IDE with the ElevenLabs Conversational AI platform through the ElevenLabs MCP Server. This integration enables voice-based Java mentoring by connecting the conversational interface with the AI development environment.

---

## Integrated Components

### Cursor IDE
- Hosts the Java Mentor AI project.
- Processes Java programming requests.
- Generates explanations, code, debugging support, and DSA guidance.

### ElevenLabs MCP Server
- Establishes communication between ElevenLabs Conversational AI and Cursor.
- Transfers user requests to Cursor.
- Returns AI-generated responses back to ElevenLabs.

### ElevenLabs Conversational AI
- Receives the user's voice input.
- Converts speech into text.
- Delivers the AI response as natural voice.

---

## Integration Workflow

1. The user asks a Java programming question.
2. ElevenLabs Conversational AI converts the voice input into text.
3. The request is sent to the ElevenLabs MCP Server.
4. The MCP Server forwards the request to Cursor.
5. Cursor processes the request and generates the appropriate Java response.
6. The response is returned through the MCP Server.
7. ElevenLabs converts the response into natural speech and delivers it to the user.

---

## Technology Stack

| Component | Purpose |
|-----------|---------|
| Cursor IDE | Java Mentor AI development and response generation |
| ElevenLabs MCP Server | Communication between Cursor and ElevenLabs |
| ElevenLabs Conversational AI | Voice interaction and speech synthesis |

### Your MCP Server
- Acts as the bridge between ElevenLabs Conversational AI and Cursor IDE.
- Receives requests from the ElevenLabs MCP Server.
- Forwards requests to Cursor.
- Returns the generated responses back to ElevenLabs for voice output.

