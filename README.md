
# Skill-Based Job Recommendation System Using AI

## Overview
A web-based AI-powered career recommendation system that analyzes a user's resume and skills to recommend suitable job roles. The system extracts skills from uploaded resumes, matches them with predefined job requirements, calculates a compatibility score, identifies skill gaps, and provides career guidance.

## Problem Statement
Most job portals provide generic recommendations based mainly on keywords and fail to accurately assess a user's actual skills and capabilities. This project aims to bridge that gap by providing personalized, skill-based job recommendations.

## Key Features
- **Resume upload and analysis** (PDF support)
- **Automatic skill extraction** from resume text
- **Skill-based job matching** against role requirements
- **Match percentage calculation** with weighted scoring
- **Missing skill identification** for career improvement
- **Career guidance** and learning path suggestions
- **Recommended hiring companies** for matched roles
- **Integration with popular job portals** via search links
- **User-friendly web interface**

## System Workflow
1. User enters personal and educational details
2. User uploads a resume
3. Resume text is extracted and processed
4. Skills are identified from the resume
5. Skills are matched with job role requirements
6. Match score is calculated
7. Best-fit job role is recommended
8. Missing skills and career guidance are displayed

## System Architecture

| Layer | Responsibilities |
| --- | --- |
| **Frontend Layer** | Collects user info, resume upload interface, displays recommendations and reports |
| **Processing Layer** | Resume parsing, skill extraction, job matching algorithm, score calculation |
| **Data Layer** | Job roles dataset, required skills database, company information |
| **Output Layer** | Recommended job role, match percentage, extracted skills, missing skills, career suggestions, job search links |

## Technologies Used

**Frontend**
- HTML
- CSS
- JavaScript

**Backend**
- Node.js
- Express.js

**Libraries**
- `Multer` - file upload handling
- `pdf-parse` - resume text extraction
- `CORS`

## Working Principle
The system extracts technical skills from the uploaded resume and compares them with predefined skill requirements for various job roles. A weighted scoring mechanism calculates the similarity score and recommends the most suitable career option.

## Example Output
Extracted Skills: Python, SQL
Recommended Role: Data Analyst
Match Score: 66%
Missing Skills: Excel

Suggested Career Path:
1. Learn Excel
2. Learn Data Visualization
3. Apply for Data Analyst positions

## Applications
- Career guidance for students
- College placement support
- Online job portals
- Skill development platforms
- Career counseling services

## Advantages
- Personalized recommendations
- Saves job-search time
- Identifies skill gaps
- Easy-to-use interface
- Structured and transparent decision-making

## Challenges
- Rule-based system limitations
- Dependency on resume quality
- Static dataset
- No real-time job market data
- Scalability constraints

## Future Enhancements
- Integration with live job APIs
- PostgreSQL database support
- Machine learning-based recommendations
- Cloud deployment (AWS/Azure)
- Real-time job market analysis

## Conclusion
The project provides a simple, efficient, and personalized job recommendation platform that helps users identify suitable career opportunities based on their skills, highlights areas for improvement, and guides them toward better career decisions.


