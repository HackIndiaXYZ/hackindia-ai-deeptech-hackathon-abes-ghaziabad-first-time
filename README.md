# hackindia-ai-deeptech-hackathon-abes-ghaziabad-first-time
Hackathon team repository for First Time - [hackindia-team:hackindia-ai-deeptech-hackathon-abes-ghaziabad:first-time]
# 🚀 CareerPilot AI
## Personalized Multi-Agent Career Intelligence Platform

CareerPilot AI is an AI-powered multi-agent career mentor platform that helps students and job seekers with:

- Resume ATS Analysis
- Skill Gap Detection
- AI Career Guidance
- Personalized Learning Roadmaps
- Mock Interview Preparation
- GitHub Skill Analysis
- LinkedIn Profile Intelligence
- Resume-Worthy Project Recommendations

The platform uses multiple AI agents powered by **Gemini + LangChain** to provide intelligent and personalized career mentorship.

---

# 🌟 Features

## 🤖 Multi-Agent AI System

| AI Agent | Responsibility |
|---|---|
| Resume Agent | Resume parsing & ATS analysis |
| Skill Agent | Skill-gap detection |
| Mentor Agent | AI career guidance chatbot |
| Roadmap Agent | Personalized roadmap generation |
| Interview Agent | Mock interview preparation |
| Project Agent | Resume-worthy project recommendations |
| Social Agent | LinkedIn profile analysis |
| GitHub Agent | GitHub skill analysis |

---

# 🧠 Problem Statement

Students and job seekers often struggle with:
- Career planning
- Resume optimization
- Skill development
- Interview preparation
- Understanding industry-relevant skills

Existing platforms provide generic recommendations instead of personalized mentorship.

CareerPilot AI solves this problem using collaborative AI agents that analyze resumes, LinkedIn profiles, GitHub profiles, and career goals to generate adaptive career guidance and intelligent learning roadmaps.

---

# 🏗 System Architecture

```text
                    USER
                      │
                      ▼
            ┌─────────────────┐
            │ Orchestrator AI │
            └────────┬────────┘
                     │
 ┌───────────────────┼────────────────────┐
 │                   │                    │
 ▼                   ▼                    ▼
Resume Agent    Social Agent       GitHub Agent
 │                   │                    │
 ▼                   ▼                    ▼
ATS Analysis   LinkedIn Insights   GitHub Skills
 │                   │                    │
 └───────────┬───────┴────────────┬───────┘
             ▼                    ▼
       Skill Agent          Mentor Agent
             │                    │
             ▼                    ▼
       Skill Gaps          Career Guidance
             │                    │
             └────────┬───────────┘
                      ▼
              Roadmap Agent
                      │
                      ▼
              Interview Agent
                      │
                      ▼
               Project Agent
                      │
                      ▼
              Personalized Output
