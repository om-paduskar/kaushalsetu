# AI Job Analyst - CV and Job Description Matching System

An intelligent CV and Job Description analysis system that extracts candidate information, evaluates job fit, identifies skill gaps, and provides an interactive chatbot for explaining the results.

## Project Overview

The AI Job Analyst is a Python-based NLP and rule-based job matching system designed to automate the initial screening and analysis of a candidate against a Job Description (JD).

The project evolved from a basic CV analyzer (V1) into an interactive CV-JD analysis chatbot (V2).

The system analyzes:

- Candidate skills
- Education
- Work experience
- Projects
- Job requirements
- Required and preferred skills
- Responsibility-level evidence
- Experience gaps
- Overall job-fit score

## Project Evolution

### V1 - CV Analyzer

The first version focused on extracting and analyzing information from a candidate's CV.

### V1 Features

- CV PDF text extraction
- Resume section identification
- Skill extraction
- Education extraction
- Experience extraction
- Basic CV-JD matching
- Project extraction
- Structured candidate profiling
- Overall match scoring

### V1 Notebook

`AI_Job_Analyst_Basic_.ipynb`

## V2 - Interactive AI Job Analyst Chatbot

V2 extends the original CV analyzer into an interactive job-analysis system.

The user can upload a CV, paste a Job Description, analyze the candidate's fit, and ask questions about the results through a chatbot interface.

### V2 Features

- CV PDF upload
- Job Description input
- Automated CV-JD analysis
- Skill matching
- Match scoring
- Education matching
- Experience matching
- Skill-gap identification
- Evidence-based analysis
- Interactive chatbot
- Gradio user interface
- Overall job-fit assessment

### Example Chatbot Questions

The chatbot can answer questions such as:

- Am I a good fit?
- What are my strengths?
- What are my skill gaps?
- How much experience do I have?
- What is my match score?
- Should I apply for this role?

### V2 Notebook

AI_Job_Analyst_V2_Chatbot.ipynb

## System Workflow

Candidate CV PDF
       |
       v
Text Extraction
       |
       v
Candidate Profile
       |
       v
Job Description Analysis
       |
       v
Skill Matching
       |
       +------------------+------------------+
       |                  |                  |
       v                  v                  v
Education            Experience       Responsibilities
Matching              Matching             Evidence
       |                  |                  |
       +------------------+------------------+
                          |
                          v
                   Overall Match Score
                          |
                          v
                  AI Job Analyst Chatbot
