# Job Orbit - Your AI Hiring Companion

## Overview of the Idea

Job Orbit is an intelligent AI-powered application that streamlines the job hunting process from search to application. It addresses several critical challenges faced by today's job seekers:

Being a full-time employee makes it extremely difficult to actively search for new opportunities. The demands of current work leave little time or energy to properly conduct a job search. Creating customized resumes for each application is time-consuming yet essential for getting past applicant tracking systems. Additionally, the networking required to secure valuable referrals adds another layer of complexity to an already overwhelming process.

Job Orbit automates these time-intensive aspects of job seeking, allowing busy professionals to maintain their current responsibilities while effectively pursuing their next career move. The application leverages advanced AI to personalize your job search experience, optimize your resume for specific roles, seek referrals on your behalf, and even submit applications—all while you focus on preparing for interviews. Job Orbit is aimed at automating this process so that when you're ready for a job switch, you don't have to worry about the logistical burden.

## Project Goal

Our goal is to revolutionize the job hunting process by creating an end-to-end automated solution that significantly reduces the time and effort required to land your next job. Job Orbit demonstrates how agentic AI systems can work seamlessly across multiple platforms (LinkedIn, resume parsing, document generation) to deliver a cohesive solution that creates tangible value for users in their professional lives.

## How It Works

### User Flow:
1. **Upload Resume:** Users upload their current resume, which serves as the ground truth for their professional information
2. **Review Extracted Details:** The system extracts and presents the key information from the resume for user verification
3. **Configure Search Parameters:** Users specify job preferences, including roles, industries, and referral settings
4. **Initiate Job Search:** With a single click, the system activates an AI agent to search LinkedIn for matching opportunities
5. **Review Discovered Opportunities:** Users can view job details discovered by the agent, including requirements and descriptions
6. **Generate Customized Resumes:** The system automatically customizes the user's base resume for specific job listings
7. **Request Referrals:** If enabled, the system identifies and contacts potential referrals through LinkedIn
8. **Apply to Jobs:** Users can trigger automated job applications with their customized resumes

### Core Functionality:
- **Intelligent Resume Parsing:** Extracts comprehensive details from PDF resumes
- **AI-Powered Job Search:** Directly integrates with LinkedIn to discover relevant opportunities
- **Resume Optimization:** Customizes resumes by strategically incorporating keywords from job descriptions
- **Automated Networking:** Identifies and contacts potential referrals with contextually appropriate messages
- **One-Click Applications:** Completes job applications by intelligently filling out forms using the customized resume content
- **Model Flexibility:** Supports multiple AI models with default configuration for AWS Bedrock models

### Multimodal Elements:
- **Document Processing:** PDF parsing for resume extraction and generation
- **Web Interaction:** Browser automation for LinkedIn interactions
- **Text Generation:** Crafting personalized messages for referral requests
- **Form Completion:** Intelligent completion of job application forms

### Tools Used:
- **Agno Agents:** Core orchestration platform for the AI agents
- **AWS Bedrock Models:** Primary intelligence layer for text processing and generation
- **BrowserUse Agent:** AI-powered browser automation for LinkedIn interaction
- **LaTeX Document Generation:** For maintaining professional formatting in customized resumes
- **PDF Processing Libraries:** For extracting information from uploaded resumes
- **LinkedIn API Integration:** For job search functionality

## UI Approach

Job Orbit features a minimalist, intuitive interface focused on guiding users through the job search process with minimal friction:

- **Upload Panel:** Simple drag-and-drop interface for resume submission
- **Information Review:** Clean, structured display of extracted resume information
- **Search Configuration:** Straightforward form for search parameter input
- **Job Results Dashboard:** Visual representation of discovered opportunities with key details
- **Resume Preview:** Side-by-side comparison of original and customized resumes
- **Process Monitoring:** Real-time status indicators for AI agent activities
- **Action Controls:** Prominent buttons for initiating key processes (search, customize, request referrals, apply)

## Demo Video

<iframe>
</iframe>
## Team Information

### Team Lead:
- **GitHub:** Rishi-Raj-Kalita
- **Background/Experience**: Data/AI consultant at AWS


### Setup Instruction
- To be added