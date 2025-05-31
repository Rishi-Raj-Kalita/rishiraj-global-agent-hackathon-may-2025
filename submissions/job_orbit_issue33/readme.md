

# Job Orbit 🚀
> Your AI-Powered Job Search Companion


## 📋 Table of Contents
- [Overview](#-overview)
- [Features](#-features)
- [Demo](#-demo)
- [Installation](#-installation)
- [Usage](#-usage)
- [Team](#-team)
- [Future Scope](#-future-scope)

## 📌 Overview

Job Orbit revolutionizes the job hunting process by leveraging AI to automate the most time-consuming aspects of job searching. Perfect for busy professionals, our solution addresses key challenges:

- **Time Management**: Automates job search while you focus on your current role
- **Resume Optimization**: AI-powered customization for each application
- **Networking**: Automated referral requests through LinkedIn
- **Application Process**: One-click applications with smart form filling

## ✨ Features

### Core Capabilities

#### 🔍 Intelligent Job Search
- LinkedIn integration
- Smart matching algorithm
- Customizable search parameters

#### 📄 Resume Enhancement
- Automatic keyword optimization
- ATS-friendly formatting
- LaTeX-based templating

#### 🤖 AI-Powered Automation
- Automated application submission
- Smart referral requests
- Intelligent form filling

## 🎥 Demo

Watch Job Orbit in action: [Demo Video](https://drive.google.com/file/d/1_eeGdMl-dlULm2U4D-6t0JfBoD8_j33n/view?usp=sharing)

## 🛠️ Installation

### Prerequisites
- Python 3.8+
- AWS Account
- LinkedIn Account

### Environment Setup

1. **Configure AWS Credentials**
```bash
export AWS_ACCESS_KEY_ID=***
export AWS_SECRET_ACCESS_KEY=***
export AWS_REGION=***
```

2. **Create Environment File**
```bash
# .env
ACCESS_KEY=***
SECRET_KEY=***
LINKEDIN_NAME=***
LINKEDIN_PASSWORD=***
```

3. **Install Dependencies**
```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

4. **Launch Application**
```bash
cd job_orbit_issue33
streamlit run App.py
```

## 💡 Usage

### Step-by-Step Guide

1. **Upload Resume**
   - Drag and drop your PDF resume
   - Review extracted information

2. **Configure Search**
   - Set job preferences
   - Define target companies

3. **Automate Applications**
   - Review matched positions
   - Trigger automated applications

## 👥 Team

### Leadership
**Rishi Raj Kalita** - _Project Lead_
- GitHub: [@Rishi-Raj-Kalita](https://github.com/Rishi-Raj-Kalita)
- Role: Data/AI Consultant at AWS

## 🔮 Future Scope

### Upcoming Features
- Memory Integration with Mem0
- Company Portal Integration
- Advanced Analytics Dashboard
- Multi-language Support

## 🛠️ Tools Used
- **Agno Agents:** Core orchestration platform
- **AWS Bedrock Models:** Primary intelligence layer
- **BrowserUse Agent:** LinkedIn automation
- **LaTeX:** Resume generation
- **Streamlit:** User interface

## 📝 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<p align="center">Made with ❤️ by the Job Orbit Team</p>


