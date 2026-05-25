# n8n
Collection of real-world automation workflows built using n8n, focusing on AI integrations, process automation, and event-driven systems.


1.📂 Current Project
  🔹 MindBinX AI — LLM-Powered Email Orchestration Platform
      An intelligent multi-AI-agent email automation workflow that monitors incoming emails in real time, classifies them using LLMs, extracts structured
      information, automates recruiter engagement, and orchestrates interview workflows with Gmail and Google Calendar integrations.
  
  📂 How to Use
  
          Import the JSON file into n8n
          Add your Gmail credentials
          Configure Gemini API key
          Activate the workflow

  ⚙️ Features
  
         - 📥 Real-Time Gmail Trigger Monitoring
         - 🧠 Multi-Agent AI Email Classification
         - 🏷️ Automatic Gmail Labeling & Routing
         - 📤 Intelligent Auto-Forwarding of Priority Emails
         - 🔍 AI-Powered Information Extraction
         - 🤖 Context-Aware Recruiter Reply Drafting
         - 📅 Automated Interview Scheduling with Google Calendar
         - 🔀 Conditional Workflow Branching & Merge Pipelines
         - ⚡ Fully Event-Driven Automation System
        
  🧠 Tech Stack
  
          Automation Engine: n8n
          AI Model(LLM / AI): Google Gemini (LLM)
          Email Integration: Gmail API
          Logic Design/Architecture: Event-Driven Multi-Agent Workflow 
          Scheduling : Google Calendar API 
          Orchestration : LangChain 

  🧠 AI Capabilities

      The workflow intelligently classifies emails into:
      
      - Recruitment
      - Interview
      - OTP / Security
      - Spam / Promotions
      - Personal
      - Generic Job Alerts
      - Others
      
      It also extracts structured metadata such as:
      
      - Company Name
      - Interview Date & Time
      - Meeting Links
      - Interview Mode
      - Recruiter Information
      
      --- 

  🏗️ Workflow Architecture
  
        Gmail Trigger → detects new emails
        AI Extractor → extracts sender info
        Conditional Logic → handles missing data
        AI Classifier → categorizes email
        Gmail Actions → apply labels + forward emails
        ```text
          Gmail Trigger
                ↓
          AI Classification Agent
                ↓
          Conditional Routing Logic
                ↓
          Information Extraction Agent
                ↓
          Recruiter Reply Agent
                ↓
          Gmail Draft Automation
                ↓
          Google Calendar Scheduling
                ↓
          Notification & Reminder System
    ```
    
  An intelligent workflow that:
    
      📥 Monitors incoming emails in real-time
      🧠 Classifies emails into categories (Jobs, Spam, OTP, Personal, Career, Others)
      🏷️ Applies labels automatically in Gmail
      📤 Forwards important emails to a secondary inbox to my main account
      🔍 Extracts sender information using AI
  
  💡 Use Cases
  
       - Intelligent inbox management
       - Recruitment email prioritization
       - Interview workflow automation
       - AI-assisted recruiter engagement
       - Spam reduction & inbox triage
       - Event-driven workflow orchestration

  🔒 Security Note

        All credentials and personal data have been removed.
        Please configure your own credentials before running the workflow.

  🚀 Upcoming Enhancements

        - Recruiter trust scoring system
        - SPF/DKIM/DMARC validation
        - AI phishing detection
        - Workflow analytics dashboard
        - Multi-channel notifications (Slack/Discord)
        - Vector memory & recruiter history tracking


📌 Repository Goal

    This repository will continuously evolve with advanced AI automation workflows, intelligent orchestration systems, and real-world event-driven automation     
    projects built using n8n and LLM ecosystems.

🚀 Upcoming Projects

This repository will be continuously updated with advanced automation workflows.
Thank you

