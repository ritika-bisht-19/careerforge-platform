# CareerForge: An AI-Powered Career Development and Placement Readiness Platform

## Abstract
Career development and placement preparation have become increasingly complex due to the availability of learning resources, coding platforms, professional networking platforms, resume-building tools, and job/internship portals across different systems. Students often rely on multiple independent platforms, resulting in fragmented career management. 

**CareerForge** is a unified, AI-powered career development and placement readiness platform. It integrates central profile management, project and certificate tracking, resume support, learning resources, coding progress monitoring, internship/job opportunities, and personalized career recommendations into a single application.

## Problem Statement
The current ecosystem requires students to navigate multiple disconnected platforms (like LinkedIn, LeetCode, GitHub) for career preparation. This fragmentation makes it difficult to maintain centralized information, identify existing skill gaps, determine required skills for specific roles, and receive customized guidance. Existing systems often focus on individual tasks rather than providing a holistic career development journey.

## Objectives
1. Develop an integrated web-based platform for student career development and placement preparation.
2. Provide centralized management of student profiles, projects, skills, and resumes.
3. Identify skill gaps by comparing a student's existing skills with predefined career requirements.
4. Implement a Rule-Based Recommendation Engine for structured career and skill-gap analysis.
5. Integrate Gemini AI for generating personalized learning roadmaps and study-material recommendations.
6. Provide AI-assisted resume improvement suggestions based on identified skill gaps.
7. Integrate GitHub and LeetCode progress to monitor technical development.
8. Offer dedicated portals for recruiters to post jobs, and for administrators to manage the platform.

## Proposed Methodology & Hybrid Architecture
CareerForge employs a **Hybrid Recommendation Approach**.

### 1. Rule-Based Recommendation Engine
This engine uses predefined "Career Skill Matrices". It compares a student's existing skills with the requirements of a selected career role, identifying missing or insufficient skills to output a clear "Skill Gap" analysis.

### 2. Generative AI (Gemini AI) Integration
The identified skill gaps, along with the student's profile and goals, are fed into the Gemini API. The AI generates personalized natural-language recommendations, including:
- Customized learning roadmaps.
- Relevant study materials.
- Actionable resume improvement suggestions.

### Workflow Example
Student Profile -> Skill Analysis -> Identify Skill Gap (Rule-Based Engine) -> Gemini AI Processing -> Personalized Recommendations -> Progress Tracking.

## System Modules
* **Student Module:** Secure authentication, career profile management, GitHub/LeetCode tracking, resume management, AI career recommendation access, and job application interface.
* **Recruiter Module:** Company profile management, job/internship posting creation, student profile/resume viewing, application tracking, and candidate shortlisting.
* **Admin Module:** Centralized control over users, recruiters, learning resources, opportunity moderation, and detailed system reporting.

## Technology Stack
* **Frontend:** HTML, CSS, JavaScript
* **Backend:** Node.js with Express.js
* **Database:** MongoDB
* **Language:** JavaScript
* **AI Engine:** Gemini API
* **External Integrations:** GitHub API, LeetCode API
* **Version Control & Hosting:** Git, GitHub
* **Development Environment:** Visual Studio Code

## Project Team
* **Anjali Rawat** (2318370)
* **Ritika Bisht** (2319422)
* **Parinita Bisht** (2319210)

**Under the Guidance of:**
Mr. Deepak Upadhyay, Assistant Professor

**Institution:**
Department of Computer Science and Engineering,
Graphic Era Hill University, Dehradun, Uttarakhand (September 2026)
