📈 Business Idea Validator Workflow

Automate business idea validation using n8n, AI analysis, and automated email reporting. Receive a business idea via webhook, generate a detailed validation report, and send it directly to the client.

Features

● Receive business idea submissions via webhook (POST /business-validator)

● Extract and format key information (idea, email, location)

● AI Agent analyzes the idea and provides:

          ● Market analysis

          ● Competitor overview

          ● SWOT analysis

          ● Actionable recommendations

● Automatically send a professional HTML email report to the client

● Fully automated workflow with minimal setup

Workflow Overview

● Webhook Node – Receives business idea submissions (idea, email, location)

● Edit Fields (Set Node) – Clean and structure incoming data for AI processing

● AI Agent (LangChain Node) – Generates a detailed validation report using GPT-4o-mini

● OpenAI Chat Model Node – Powers the AI Agent for intelligent analysis

● Send Email (Gmail Node) – Sends a well-formatted HTML report to the client

Example Input
{
  "idea": "Eco-friendly Car Wash in Islamabad",
  "email": "client@example.com"
}
Example Output

● Market Analysis: Urban car wash demand, growth trends

● Competitor Overview: Local services, mobile car wash, automated stations

● SWOT Analysis: Strengths, Weaknesses, Opportunities, Threats

● Recommendations: Marketing strategies, eco-friendly options, loyalty programs

📄 License

This project is licensed under the MIT License. You are free to use, modify, and distribute the workflow for personal or commercial purposes.

👤 Author

Abdullah Aqeel

AI Automation Engineer | Software Quality Assurance Engineer (SQAE)
