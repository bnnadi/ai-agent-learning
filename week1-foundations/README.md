# Week 1: Foundations + Teams Bot Basics

**Focus:** Learn the fundamentals and get your first Teams bot working

## Daily Breakdown

### Day 1 (3 hours) - Setup & Foundation
**Deliverable:** Working "Hello World" Teams bot

- **Hour 1:** Environment Setup
  - Install Node.js, VS Code with Teams Toolkit extension
  - Create Microsoft 365 Developer account (free)
  - Set up Azure account (free tier)

- **Hour 2:** First Teams Bot
  - Follow "Build your first Teams bot" tutorial
  - Use Teams Toolkit in VS Code
  - Get "Hello World" bot responding in Teams
  - Test locally

- **Hour 3:** Understand Architecture
  - Read Teams Bot architecture docs
  - Understand Bot Framework SDK basics
  - Draw architecture diagram
  - Document what you learned

---

### Day 2 (3 hours) - LangChain Refresher
**Deliverable:** LangChain chatbot with conversation memory

- **Hour 1-2:** DeepLearning.AI Course
  - Complete "LangChain for LLM Application Development" Modules 1-3
  - Focus on Models, Prompts, Parsers, and Memory
  - Run all code examples locally

- **Hour 3:** Quick Build
  - Build simple chatbot with memory using LangChain
  - Test different conversation flows
  - Save to GitHub repo

---

### Day 3 (3 hours) - Introduction to LangGraph
**Deliverable:** Working LangGraph agent with 3 tools

- **Hour 1:** Study LangGraph
  - Read LangGraph documentation overview
  - Watch "LangGraph Introduction" video
  - Understand: Why LangGraph vs LangChain?
  - Key concept: State graphs for agents

- **Hour 2:** First LangGraph Agent
  - Follow LangGraph quickstart tutorial
  - Build agent with 2 tools (calculator, search)
  - Understand the agent loop: plan → act → observe

- **Hour 3:** Experiment
  - Add a third tool to your agent
  - Test different types of queries
  - Document how the agent makes decisions

---

### Day 4 (3 hours) - N8N Setup & Basics
**Deliverable:** N8N workflow that processes AI requests

- **Hour 1:** Install N8N
  - Install N8N locally: `npx n8n`
  - Complete N8N quickstart tutorial
  - Build first workflow: HTTP trigger → OpenAI → Response

- **Hour 2:** Explore N8N
  - Build workflow: Webhook → Process data → Call API
  - Test with Postman or curl
  - Understand N8N's node system
  - Explore AI-related nodes

- **Hour 3:** N8N + AI Integration
  - Build workflow that calls OpenAI API
  - Add error handling
  - Add data transformation
  - Export workflow and save to GitHub

---

### Day 5 (3 hours) - Connect Teams Bot to Basic API
**Deliverable:** Teams bot that calls external API

- **Hour 1:** Teams Bot Enhancement
  - Modify your Teams bot to accept commands
  - Add slash commands (e.g., `/hello`, `/help`)
  - Test command parsing

- **Hour 2:** Build Simple API
  - Create Express.js API with one endpoint
  - Endpoint receives text, returns processed response
  - Test with Postman

- **Hour 3:** Connect Bot to API
  - Have Teams bot call your API when user sends message
  - Display API response in Teams
  - Test end-to-end flow
  - Document architecture

---

### Day 6 (3 hours) - Azure Deployment Basics
**Deliverable:** Teams bot running in Azure

- **Hour 1:** Azure Setup
  - Create Azure Bot Service resource
  - Configure bot authentication
  - Understand Azure Bot Channels

- **Hour 2:** Deploy Bot to Azure
  - Use Teams Toolkit to deploy
  - Configure environment variables
  - Test deployed bot in Teams

- **Hour 3:** Troubleshooting & Docs
  - Fix any deployment issues
  - Set up logging/monitoring
  - Document deployment process
  - Create deployment checklist

---

### Day 7 (3 hours) - Week 1 Review & Portfolio
**Deliverable:** Week 1 summary blog post + organized portfolio

- **Hour 1:** Clean Up Projects
  - Organize all GitHub repos
  - Add READMEs to each project
  - Add architecture diagrams
  - Add screenshots/demos

- **Hour 2:** Write Blog Post
  - Title: "Building My First Teams Bot with AI Integration"
  - Document what you learned
  - Include code snippets
  - Share challenges and solutions

- **Hour 3:** Plan Week 2
  - Review what worked/didn't work
  - Adjust learning approach if needed
  - Set specific goals for Week 2
  - Rest and reflect

---

## Success Metrics

By the end of Week 1, you should have:
- ✅ Working Teams bot deployed to Azure
- ✅ Understanding of LangChain and LangGraph basics
- ✅ Built first agent with tools
- ✅ N8N workflow connected to bot

---

## Resources

- [Teams Bot Framework Docs](https://learn.microsoft.com/en-us/microsoftteams/platform/bots/what-are-bots)
- [LangChain Docs](https://python.langchain.com/docs/get_started/introduction)
- [LangGraph Docs](https://langchain-ai.github.io/langgraph/)
- [N8N Docs](https://docs.n8n.io/)
- [DeepLearning.AI LangChain Course](https://www.deeplearning.ai/short-courses/langchain-for-llm-application-development/)

