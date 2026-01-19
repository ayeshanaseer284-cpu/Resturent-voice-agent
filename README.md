Restaurant Voice Agent (n8n Workflow)

Project Overview
The Restaurant Voice Agent is an AI-powered automation system built using n8n, OpenAI, and Pinecone. It works as a virtual restaurant assistant that receives customer messages through a webhook, understands user queries using an AI agent, and provides accurate responses by retrieving relevant information from a knowledge base.

This project is ideal for restaurants, food delivery services, and AI-based customer support systems.

Features
• AI-powered restaurant assistant
• Webhook-based communication
• Intelligent query understanding using OpenAI models
• Knowledge retrieval using Pinecone vector database
• Real-time automated responses
• Developed using low-code automation with n8n

Workflow Components
• Webhook node for receiving customer requests
• AI Agent (LangChain) for processing and reasoning
• OpenAI Chat Model for response generation
• OpenAI Embeddings for converting text into vectors
• Pinecone Vector Store for storing and retrieving restaurant data
• Respond to Webhook node for sending replies back to users

Technology Stack
• n8n
• OpenAI API
• LangChain
• Pinecone
• REST Webhooks

Project Structure
Resturent voice agent.json
README.md

Setup Instructions

Prerequisites
n8n installed locally or on the cloud
OpenAI API key
Pinecone account with an active index
Basic understanding of n8n workflows

Importing the Workflow

Open n8n

Click on Import Workflow

Upload the file Resturent voice agent.json

Save the workflow

Credential Configuration
Add OpenAI API credentials in n8n
Add Pinecone API credentials
Make sure the Pinecone index name is set to
resturentagent

Activating the Workflow
Enable the workflow in n8n
Copy the generated webhook URL
Send POST requests containing customer messages

Example Webhook Request
{
"message": "What items are available on the menu?"
}

Use Cases
Restaurant order assistance
Menu and pricing inquiries
Customer support automation
Chat or voice-based food ordering
Internship or final year academic project

Future Enhancements
Voice-to-text support
Order placement and tracking
WhatsApp or phone call integration
Admin dashboard for restaurant owners
Multi-language support

Author
Ayesha Naseer
AI Automation Enthusiast

License
This project is open-source and free to use for educational and development purposes.
