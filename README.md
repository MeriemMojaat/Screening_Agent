# 🤖 AI Screening Agent

> **CV + JD in, real interview practice out.**

The **AI Screening Agent** is an AI-powered interview preparation and candidate screening platform designed to make interview practice more realistic, personalized, explainable, and fair.

Inspired by the idea of a **flight simulator**, the platform provides candidates with a safe environment where they can practice realistic interviews, receive live feedback, identify skill gaps, and measure their overall interview readiness before facing a real recruiter.

The platform analyzes a candidate's **CV/LinkedIn profile** together with a **Job Description (JD)** to generate a personalized interview experience.

---

## ✈️ The Idea

> *Pilots don't learn during a storm; they learn in a flight simulator.*

Traditional interview preparation is often based on guesswork:

* ❌ Candidates don't know whether their CV matches the job.
* ❌ Interview preparation is often unstructured.
* ❌ Feedback is vague or only provided after the interview.
* ❌ Candidates struggle to identify their real skill gaps.
* ❌ Generic interview questions don't reflect the target position.
* ❌ Black-box AI scores can be difficult to trust.
* ❌ Fairness and privacy are often treated as secondary concerns.

The AI Screening Agent addresses these problems by combining **CV/JD analysis, AI-powered interviews, speech analysis, real-time coaching, explainable scoring, and readiness assessment** into one platform.

### In one line:

**CV + JD → Skill Gap Analysis → AI Mock Interview → Real-Time Feedback → Explainable Score → Readiness Index**

---

# 🎯 Project Goals

The project aims to:

* 🎤 Provide realistic AI-powered mock interviews.
* 📄 Analyze CVs against specific job descriptions.
* 🧩 Identify candidate skill gaps.
* 🤖 Generate JD-aware interview questions.
* 💡 Provide actionable feedback during interviews.
* 📝 Transcribe candidate answers in real time.
* 📊 Evaluate content, delivery, and communication.
* 🎯 Calculate an overall interview Readiness Index.
* 🔎 Provide transparent and explainable scores.
* 🌍 Support multilingual interview preparation.
* ⚖️ Incorporate fairness and bias mitigation.
* 🔐 Protect candidate privacy and sensitive information.

---

# 👥 Target Personas

## 🎓 Sami — Student in Tunisia

> *"I just need someone to tell me if I'm interview-ready."*

**Needs:**

* Structured interview practice
* Job-specific preparation
* Confidence building
* Measurable progress

---

## 🌍 Rim — Student Abroad

> *"I want to know how to interview successfully in this country."*

**Needs:**

* Role-specific preparation
* International interview preparation
* Multilingual support
* Culturally adapted communication guidance

---

## 🔄 Nadia — Career Switcher

> *"I need to know if my experience transfers well to this new career."*

**Needs:**

* Transferable skill identification
* CV/JD matching
* Targeted preparation
* Identification of critical skill gaps

---

## 🗣️ Raj — Non-Native Speaker

> *"My skills are strong, but I need help telling my story clearly in English."*

**Needs:**

* Speech clarity support
* Fluency improvement
* Filler-word awareness
* Communication coaching
* Accent-neutral evaluation

---

## 👩‍💼 Sarah — High-Volume Recruiter

> *"I need a reliable, explainable first filter so I can focus my time on the best candidates."*

**Needs:**

* Efficient candidate screening
* Explainable scoring
* Fair evaluation
* Reliable candidate filtering

---

## 👨‍💻 Mark — Niche Technical Recruiter

> *"I need to know every candidate truly has the technical skills for the role."*

**Needs:**

* Technical skill validation
* Adaptive technical interviews
* Evidence-based scoring
* Skill verification

---

# 🚀 Core Features

## 1. 🤖 AI Bot & Avatar Interview System

The interview system is the core of the platform.

### JD-Aware Question Generation

The system analyzes the target Job Description and generates questions relevant to the specific position.

For example:

```text
Data Scientist JD
        ↓
Required Skills
        ↓
Python • SQL • Machine Learning • Cloud
        ↓
Personalized Interview Questions
```

This avoids generic interview questions and creates a **job-specific interview experience**.

### AI Avatar Mock Interview

Candidates interact with an AI interviewer through an avatar-based interview experience.

The system can simulate:

* Behavioral questions
* Technical questions
* Situational questions
* Motivational questions
* Company-specific questions

### Video Recording & Playback

Interview answers can be recorded and reviewed so candidates can analyze their own performance.

### AI-Powered Highlights

The system identifies strong moments and important sections of the interview, helping candidates focus their review.

---

# 2. 🎙️ Real-Time Transcription

Candidate speech is converted into text during the interview.

The transcript provides the foundation for several downstream features:

* Answer analysis
* Keyword detection
* Filler-word detection
* Content scoring
* STAR analysis
* Communication analysis
* Interview feedback

---

# 3. 📄 CV–JD Matching

The platform compares the candidate's CV with the target Job Description.

### Match Percentage

The system provides an easy-to-understand alignment score.

Example:

```text
CV ↔ Job Description

Match: 73%
```

This gives candidates an immediate understanding of how closely their profile matches the role.

### Skill Gap Map

The system identifies:

* ✅ Skills that are clearly present
* 🟡 Skills that are partially represented
* ❌ Missing or insufficiently represented skills

Example:

```text
Python              ✅ Strong
SQL                 🟡 Partial
AWS                 ❌ Missing
Machine Learning    ✅ Strong
Stakeholder Mgmt    🟡 Partial
```

This allows candidates to focus their preparation on the most important gaps.

---

# 4. 💡 Smart Feedback Suite

The platform provides real-time and post-interview feedback.

### Real-Time Coaching

Candidates receive contextual suggestions while answering.

Example:

```text
💡 Consider adding a measurable result.
```

### Answer Length Analysis

The system monitors answer duration and helps candidates avoid answers that are excessively short or long.

### Keyword Checklist

Important skills and concepts extracted from the JD can be tracked during the answer.

```text
☑ Python
☑ Machine Learning
☐ AWS
☑ SQL
```

### Filler Word Detection

The system identifies common filler words such as:

* "um"
* "uh"
* "like"
* "you know"
* "basically"

Candidates can use this information to improve speech clarity and reduce unnecessary hesitation.

### Speech Pace & Tone

The platform analyzes speech characteristics such as:

* Speaking rate
* Pace
* Tone variation
* Clarity
* Hesitation patterns

### STAR Coaching

The system evaluates whether answers contain the four STAR components:

```text
S — Situation
T — Task
A — Action
R — Result
```

If an answer is missing an important component, the system can provide a corresponding coaching suggestion.

### Confidence Feedback

The platform provides suggestions related to communication and delivery.

### Answer Ranking

After several questions, answers can be ranked based on their overall quality, allowing candidates to quickly identify their strongest and weakest responses.

---

# 5. 📊 Explainable Scoring System

A key principle of the project is:

> **"Learning happens when you understand why, not just what."**

Instead of producing a black-box score, the platform breaks the evaluation into understandable dimensions.

## Final Score

The interview score is calculated using:

```text
FINAL SCORE =
(Content × 45%)
+
(Delivery × 35%)
+
(Communication × 20%)
```

### 🧠 Content — 45%

Evaluates **what the candidate says**.

Criteria include:

* Relevance to the question
* STAR structure
* Job-description keyword coverage
* Specificity
* Quantification
* Examples and evidence

### 🎤 Delivery — 35%

Evaluates **how the candidate communicates**.

Criteria include:

* Speech pace
* Filler-word frequency
* Tone variation
* Answer duration
* Speech clarity

### 💬 Communication — 20%

Evaluates the clarity and professionalism of the response.

Criteria include:

* Logical flow
* Coherence
* Professional language
* Hesitation patterns
* Communication confidence

---

# 6. 🎯 Readiness Index

Individual question scores don't necessarily answer the most important question:

> **"Am I ready for the entire interview?"**

The **Readiness Index** provides a holistic assessment of interview preparedness for a specific job.

## Formula

```text
READINESS INDEX =
(Average Answer Quality × 40%)
+
(Consistency × 25%)
+
(JD Match × 20%)
+
(Progress × 10%)
+
(Coverage × 5%)
```

### Components

| Component              | Weight | Description                          |
| ---------------------- | -----: | ------------------------------------ |
| Average Answer Quality |    40% | Mean score across practice questions |
| Consistency            |    25% | Stability of performance             |
| JD-Specific Match      |    20% | Alignment with job requirements      |
| Progress               |    10% | Improvement across sessions          |
| Coverage               |     5% | Breadth of practiced question types  |

### Readiness Interpretation

|  Score | Interpretation       |
| -----: | -------------------- |
| 85–100 | 🟢 Highly Ready      |
|  75–84 | 🟢 Ready             |
|  65–74 | 🟡 Approaching Ready |
|  50–64 | 🟠 Needs Practice    |
|   < 50 | 🔴 Not Ready         |

The objective is to transform:

> *"I hope I'm ready."*

into:

> **"I know where I stand and what I need to improve."**

---

# 7. 🌍 Multilingual Support

The platform is designed to support international candidates.

### Initial Languages

* 🇬🇧 English
* 🇫🇷 French
* 🇹🇳 Arabic

### Accent Variations

The planned system supports different English accent variations, including:

* US English
* UK English
* Indian English

Multilingual capabilities allow candidates to practice interviews in the language most relevant to their target position and market.

---

# 8. ⚖️ Fairness & Bias Mitigation

Fairness is considered a core requirement rather than an optional feature.

The platform is designed to reduce the influence of irrelevant personal characteristics on candidate evaluation.

## Bias & Fairness Monitoring

The system can monitor scoring patterns across demographic groups using fairness metrics such as:

* Demographic parity
* Equal opportunity
* Calibration

## Resume Anonymization

Potentially bias-inducing information can be removed before analysis, including:

* Names
* Photos
* Addresses
* Graduation years
* Other personally identifiable information

The focus remains on:

* Skills
* Experience
* Achievements
* Job-relevant information

## Fairness Dashboard

A dedicated monitoring layer can provide:

* Score distributions
* Group-level performance metrics
* Potential disparity alerts
* Feature-level analysis

---

# 9. 🔐 Privacy & Security

Candidate data can contain highly sensitive information, particularly CVs and interview recordings.

The planned production architecture therefore emphasizes:

* Encryption in transit
* Encryption at rest
* Strict access control
* User consent
* Data ownership
* Data deletion
* Secure storage

The system is designed with **privacy by design** as a core principle.

---

# 10. 📄 CV Analysis

The CV Analysis feature helps candidates improve their resumes before applying.

### Resume Structure & Readability

Evaluates:

* Organization
* Structure
* Readability
* Section consistency

### Keyword & Tone Analysis

Identifies:

* Relevant skills
* Industry keywords
* Achievements
* Professional language
* Tone

### Improvement Suggestions

Provides actionable recommendations such as:

* Adding measurable achievements
* Improving wording
* Highlighting transferable skills
* Strengthening relevant keywords

The feature combines **NLP and rule-based parsing**.

Rule-based parsing uses predefined patterns and rules to identify elements such as:

```text
"Experience" → Experience section
"Education" → Education section
"2024–2026" → Date information
"Python" → Technical skill
```

---

# 💼 Future Job Hunt Mode

A future extension of the platform is a complete job-search companion.

The planned workflow is:

```text
Discover Job
     ↓
Analyze CV ↔ JD
     ↓
Calculate Match
     ↓
Identify Skill Gaps
     ↓
Practice Interview
     ↓
Track Readiness
     ↓
Apply Confidently
```

Potential integrations include job platforms such as LinkedIn and Indeed, subject to their available APIs and usage policies.

---

# 🧪 Prototype Features

The following features are considered prototype or validation-stage capabilities:

* 🎮 Gamification
* 📈 Personalized improvement plans
* 🤖 Recruiter-side AI chatbot
* 🛡️ Question safety checker
* 🃏 Rubric flashcards

These features require further user validation and experimentation before production deployment.

---

# 🔮 Future Perspective

The project can be extended with:

### 🥽 VR Avatar Mode

Immersive interview simulation using virtual reality avatars.

### ✍️ AI CV Corrector / Generator

AI-assisted CV creation and optimization based on target job descriptions.

### 🎯 Job Fit Probability

Prediction of candidate-role fit using:

* CV
* JD
* Skills
* Interview performance
* Historical data

---

# 🏗️ Technical Pipeline

The overall system follows this conceptual pipeline:

```text
                ┌──────────────────┐
                │   Candidate CV   │
                └────────┬─────────┘
                         │
                         ▼
                ┌──────────────────┐
                │   Job Description│
                └────────┬─────────┘
                         │
                         ▼
              ┌──────────────────────┐
              │ CV / JD Analysis     │
              │ & Skill Matching     │
              └──────────┬───────────┘
                         │
                         ▼
                ┌──────────────────┐
                │ Skill Gap Map    │
                └────────┬─────────┘
                         │
                         ▼
              ┌──────────────────────┐
              │ JD-Aware Question    │
              │ Generation           │
              └──────────┬───────────┘
                         │
                         ▼
              ┌──────────────────────┐
              │ AI Mock Interview    │
              │ + Avatar             │
              └──────────┬───────────┘
                         │
                         ▼
              ┌──────────────────────┐
              │ Speech Recognition   │
              │ & Transcription      │
              └──────────┬───────────┘
                         │
                         ▼
          ┌───────────────────────────────┐
          │ Smart Feedback & Analysis    │
          │                               │
          │ • Content                     │
          │ • Delivery                    │
          │ • Communication               │
          │ • STAR                        │
          │ • Keywords                    │
          │ • Fillers                     │
          │ • Pace / Tone                 │
          └───────────────┬───────────────┘
                          │
                          ▼
              ┌──────────────────────┐
              │ Explainable Score    │
              └──────────┬───────────┘
                         │
                         ▼
              ┌──────────────────────┐
              │ Readiness Index      │
              └──────────┬───────────┘
                         │
                         ▼
              ┌──────────────────────┐
              │ Personalized Report  │
              │ & Recommendations    │
              └──────────────────────┘
```

---

# 📌 Project Scope

### Current Focus

The primary focus is the **candidate-side interview preparation experience**.

The core workflow is:

1. Upload CV/LinkedIn information.
2. Provide a Job Description.
3. Analyze CV–JD alignment.
4. Display the Skill Gap Map.
5. Generate JD-aware interview questions.
6. Conduct an AI mock interview.
7. Transcribe and analyze answers.
8. Provide feedback.
9. Calculate interview scores.
10. Generate the Readiness Index.
11. Produce a final preparation report.

### Production Direction

The production-oriented architecture emphasizes:

* Privacy
* Security
* Explainability
* Fairness
* Scalability
* Multilingual support

---

# 📚 Research & Methodological Foundations

Several components of the project are inspired by research in:

* Structured interviews
* Interview validity
* Candidate evaluation
* Communication and delivery
* Algorithmic fairness
* Explainable AI
* Natural Language Processing
* Speech analysis

The scoring framework particularly emphasizes structured evaluation rather than relying on a single opaque model.

---

# 👨‍💻 Project Team

### Yosr Charrada

📧 [yosr.chaarrada@esprit.tn](mailto:yosr.chaarrada@esprit.tn)

### Maram Sliti

📧 [maram.sliti@esprit.tn](mailto:maram.sliti@esprit.tn)

### Tessnim Etteib

📧 [tessnim.etteib@esprit.tn](mailto:tessnim.etteib@esprit.tn)

### Nour Amorri

📧 [nour.amorri@esprit.tn](mailto:nour.amorri@esprit.tn)

### Meriem Mojaat

📧 [mojaat.meriem@esprit.tn](mailto:mojaat.meriem@esprit.tn)

---

# 📋 Project Status

**Status:** 🚧 Prototype / Development

The project is being developed incrementally, with the candidate interview experience forming the core of the current implementation.

---

# 🎯 Vision

The AI Screening Agent aims to transform interview preparation from a stressful guessing game into a **measurable, personalized, and realistic practice experience**.

Instead of asking:

> *"Am I ready for this interview?"*

the candidate should be able to ask:

> **"What are my gaps, how am I performing, and exactly what should I improve?"**

### ✈️ CV + JD in, real practice out.
