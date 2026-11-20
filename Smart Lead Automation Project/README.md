
# Smart Lead Automation System

An AI-powered workflow for automated lead collection, qualification, scoring, classification, routing, and personalized email communication.

## Project Overview

The Smart Lead Automation System automates the lead management process using workflow automation and Artificial Intelligence. It collects lead information, analyzes customer requirements, assigns a qualification score, categorizes leads, updates records, and sends personalized emails automatically.

The system helps reduce manual effort and improves the efficiency of lead management and follow-up.

## Objectives

- Automate lead collection.
- Analyze leads using AI.
- Score leads based on purchasing intent and requirements.
- Categorize leads into Hot, Warm, and Cold.
- Automatically route leads according to their classification.
- Update lead records in Google Sheets.
- Send personalized email communication.

## Technologies Used

- n8n — Workflow automation
- Google Forms — Lead data collection
- Google Sheets — Lead database and record management
- Google Gemini AI — Lead analysis and qualification
- Gmail — Automated email communication

## Workflow Architecture

Google Forms
↓
Google Sheets
↓
n8n Workflow Trigger
↓
AI Lead Analysis (Google Gemini)
↓
Lead Scoring & Classification
↓
Hot / Warm / Cold Routing
↓
Google Sheets Update
↓
Automated Email Communication

## Key Features

### AI-Powered Lead Qualification
Analyzes lead information, requirements, budget, urgency, and purchasing intent.

### Lead Scoring
Assigns a score from 0 to 100 to evaluate lead quality and readiness.

### Automatic Classification

- 🔥 Hot Leads — High purchasing intent and readiness
- 🟡 Warm Leads — Genuine interest with further nurturing required
- ❄️ Cold Leads — Low purchasing intent or exploratory inquiries

### Automated Routing
Uses conditional workflow logic to route leads into the appropriate Hot, Warm, or Cold branch.

### Database Management
Automatically updates lead information, qualification scores, classification, requirement analysis, and recommended actions in Google Sheets.

### Personalized Email Automation
Generates and sends appropriate email communication based on the lead's classification.

## Workflow Implementation

The workflow is implemented using n8n and integrates Google Forms, Google Sheets, Google Gemini AI, and Gmail.

The AI Agent evaluates incoming lead information and generates a qualification score, lead category, requirement analysis, recommended next action, and personalized email content.

The Switch node routes leads into their respective branches based on their classification.

## Testing

The workflow was tested with sample leads representing different qualification categories.

The Hot, Warm, and Cold classification and routing branches were tested, and automated email execution was verified.

## Project Demonstration

[Watch the Project Demonstration Video](Smart%20Lead%20Automation%20Project/demo.md)

## Project Screenshots

Screenshots of the workflow, lead classification, routing, and database results are available in the repository.

## Project Documentation

The project report and supporting documentation are available in the Documentation folder.

## Future Improvements

- CRM integration
- WhatsApp automated follow-ups
- Advanced lead analytics dashboard
- Lead nurturing sequences
- Improved AI-based prediction and scoring
- Integration with additional business tools

## Author

**Aditya Pratap Singh**

B.Tech — Computer Science & Engineering  
Parul University

## License

This project is created for educational, learning, and demonstration purposes.

