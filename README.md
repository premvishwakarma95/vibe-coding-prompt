# vibe-coding-prompt

## (Vibe Coding instruction) Full Stack AI Based Website Flow Google sheet.
https://docs.google.com/document/d/1rRhMlKmLTwfCyNg4yekoDtEzK_qg11v-P9mn7rliexM/edit?tab=t.nx1z5ojdjhdq

---

## Prompt Generator AI Agent.
```
You are an expert AI prompt engineer, senior full-stack developer, and product architect.

Your task is to convert my business idea into a high-quality, detailed, production-ready prompt that can be used in AI website builders (Lovable, Bolt, Cursor, v0, GPT, etc.) to generate a complete working website.

---

OBJECTIVE

Analyze my input carefully and generate a final website-generation prompt that includes:

- Clear technical requirements
- UI/UX specifications
- Feature list
- Page structure
- Tech stack
- API / automation logic
- Constraints
- Output expectations

The final prompt must be specific, structured, and actionable.
No vague language.

---

INPUT FORMAT (FROM ME)

I will provide:

Business Name:
Industry:
Main Problem:
Solution:
Target Users:
Core Feature:
USP:
Backend / Automation Setup:
Monetization Model:
Theme / Branding:

---

YOUR TASK

When I give input:

1. Understand the business completely.
2. Identify missing details and logically fill small gaps.
3. Improve clarity and feasibility.
4. Convert the idea into a technical product brief.
5. Transform the brief into a single powerful AI prompt.
6. Optimize it for website generation tools.

---

PROMPT GENERATION RULES

The generated prompt MUST include:

1. Role Definition (Senior Engineer + Designer)
2. System Constraints (Backend, storage, auth, APIs)
3. Functional Requirements (Exact user flows)
4. Non-Functional Requirements (Speed, security, UX, scalability)
5. Page Structure (All screens)
6. UI/UX Rules (Layout, colors, responsiveness)
7. Technical Stack (Frameworks, libraries)
8. Integration Logic (APIs, webhooks, automation)
9. Output Expectations (Code quality, structure)
10. Restrictions (What NOT to build)

---

DO NOT

- Ask unnecessary questions
- Leave placeholders
- Use generic words like "nice UI" or "good performance"
- Produce partial prompts
- Skip technical details

---

OUTPUT FORMAT (STRICT)

Return ONLY this:

---

FINAL WEBSITE GENERATION PROMPT


---

No explanation.
No commentary.
No extra text.

Only the final prompt.

---

QUALITY STANDARD

The output prompt must be:

- Ready for direct use
- Clear to engineers
- Suitable for production
- Detailed enough for real deployment
- Optimized for AI website builders
```

---

## How to use this prompt generator.
- First paste this prompt in gpt then it will ask some questions about your project.
- Then paste that questions you were asked and also tell about your project and tell gpt to give these questions answers in this format about your project.
- Discuss abuot your project then get that asked questions answers in this format and paste in prompt generator chat then you will final prompt that you will give to your IDE integrated LLM.
- Best thing first discuss about the project in the chat all things.

---

## 1️⃣ Folder Structure
```
You are a senior software architect. I will describe my project in a few lines and also provide the tech stack I want to use. Your job is to design a complete folder structure for my web application.

My Project:
[DESCRIBE YOUR PROJECT IN 2-5 LINES HERE]
Example - attendance management app there would be admin who will create employee if empty login then punch in if logout then punch out show all attendance of eamch empty for a month and perday time like he worked 8 hours 7 hours kind of  

My Tech Stack:
- Frontend: [e.g. React, Next.js]
- Backend: [e.g. Node.js, Django]
- Database: [e.g. PostgreSQL, MongoDB]
- Authentication: [e.g. JWT, Firebase Auth]

Please provide:
- Complete folder/file structure for both frontend and backend
- A short comment next to each folder explaining what goes inside it

Keep it simple, clear, and beginner-friendly.
```

---

## 2️⃣ Database Schema
```
You are a senior backend developer.

My Project:
[DESCRIBE YOUR PROJECT IN 2-5 LINES]

My Database: [e.g. PostgreSQL, MongoDB]

Generate a complete database schema:
- All tables/collections with field names and data types
- Primary keys, foreign keys, and relations
- Add a one-line comment on each table explaining its purpose
Keep it simple and beginner-friendly.
```

---

## 3️⃣ API Design
```
You are a senior backend developer.

My Project:
[DESCRIBE YOUR PROJECT IN 2-5 LINES]

My Backend: [e.g. Node.js + Express, Django]

Generate a complete REST API design:
- All endpoints with method (GET, POST, PUT, DELETE)
- Route path
- Request body / params
- Response structure
- Which role can access it (e.g. admin, user, public)
Keep it simple and beginner-friendly.
```

---

## 4️⃣ Authentication Flow
```
You are a senior backend developer.

My Project:
[DESCRIBE YOUR PROJECT IN 2-5 LINES]

My Auth Method: [e.g. JWT, Firebase Auth, OAuth]
My Backend: [e.g. Node.js, Django]

Generate the complete authentication flow:
- Register flow (step by step)
- Login flow (step by step)
- Token generation and verification
- Protected route handling
- Logout flow
Explain each step simply for a beginner developer.
```

---

## 5️⃣ Frontend Components
```
You are a senior frontend developer.

My Project:
[DESCRIBE YOUR PROJECT IN 2-5 LINES]

My Frontend: [e.g. React, Next.js, Vue]

Generate a complete frontend component breakdown:
- List all pages and their purpose
- For each page list the components used inside it
- Show the component hierarchy (parent → child)
- Add a one-line description for each component
Keep it simple and beginner-friendly.
```

---

## 6️⃣ Feature Code
```
You are a senior full stack developer.

My Project:
[DESCRIBE YOUR PROJECT IN 2-5 LINES]

My Tech Stack:
- Frontend: [e.g. React]
- Backend: [e.g. Node.js + Express]
- Database: [e.g. MongoDB]

Feature I want to build:
[DESCRIBE THE SPECIFIC FEATURE IN 2-3 LINES]

Write complete working code for this feature:
- Backend: API route + logic + DB query
- Frontend: UI + API call + state handling
Add comments in the code so a beginner can understand each step.
```

## 7️⃣ Debugging
```
You are a senior developer and expert debugger.

My Tech Stack: [e.g. React + Node.js + MongoDB]

The feature I was building:
[DESCRIBE WHAT YOU WERE TRYING TO DO]

The problem I am facing:
[DESCRIBE THE BUG OR ERROR]

My current code:
[PASTE YOUR CODE HERE]

Error message (if any):
[PASTE ERROR HERE]

Find the bug, explain why it happened in simple words,
and give me the fixed code with comments.
```

---

## 8️⃣ Testing
```
You are a senior QA and backend developer.

My Tech Stack: [e.g. Node.js + Jest, React + React Testing Library]

The module/feature I want to test:
[DESCRIBE THE FEATURE]

Code to test:
[PASTE YOUR CODE HERE]

Generate complete test cases:
- Unit tests for each function/component
- Edge cases to cover
- Use simple comments to explain what each test is checking
Keep it beginner-friendly.
```

---

## 9️⃣ Documentation
```
You are a senior technical writer and developer.

My Project:
[DESCRIBE YOUR PROJECT IN 2-5 LINES]

My Tech Stack:
- Frontend: [e.g. React]
- Backend: [e.g. Node.js]
- Database: [e.g. PostgreSQL]

Generate complete project documentation:
1. README.md — project overview, setup steps, how to run locally
2. API Docs — all endpoints with method, route, request, response
3. Folder Structure explanation
4. Environment variables needed (.env example)
Write it clearly so any beginner developer can read and understand.
```

---

# More shorter prompt.

## 🔁 The Ideal Flow in Cursor
```
Prompt 1 → Get structure → Accept it
Prompt 2 → Get schema → Accept it
Prompt 3 → Get APIs → Accept it
Prompt 4 → Get auth → Test it
Prompt 5 → Get components → Accept it
Prompt 6 → One feature at a time → Test each one
Prompt 7 → Fix bugs as they come
Prompt 8 → Write tests at the end
Prompt 9 → Generate docs last
```

---

## 1️⃣ Project Setup (Fill this ONCE — use it everywhere)
```
You are a senior software architect. I will describe my project 
and tech stack once. Remember this for all my upcoming prompts.

My Project:
[DESCRIBE YOUR PROJECT IN 2-5 LINES]

My Tech Stack:
- Frontend: [e.g. React, Next.js]
- Backend: [e.g. Node.js, Django]
- Database: [e.g. PostgreSQL, MongoDB]
- Authentication: [e.g. JWT, Firebase Auth]

Acknowledge this and wait for my next instruction.
```

---

## 2️⃣ Folder Structure
```
Based on the project and tech stack I already provided,
generate a complete folder/file structure for both frontend and backend.
Add a short comment next to each folder explaining what goes inside it.
```

---

## 3️⃣ Database Schema
```
Based on the project and tech stack I already provided,
generate a complete database schema:
- All tables/collections with field names and data types
- Primary keys, foreign keys and relations
- One-line comment on each table explaining its purpose
```

---

## 4️⃣ API Design
```
Based on the project and tech stack I already provided,
generate a complete REST API design:
- All endpoints with method (GET, POST, PUT, DELETE)
- Route path
- Request body / params
- Response structure
- Which role can access it (admin, user, public)
```

---

## 5️⃣ Authentication Flow
```
Based on the project and tech stack I already provided,
generate the complete authentication flow:
- Register flow (step by step)
- Login flow (step by step)
- Token generation and verification
- Protected route handling
- Logout flow
```

---

## 6️⃣ Frontend Components
```
Based on the project and tech stack I already provided,
generate a complete frontend component breakdown:
- All pages and their purpose
- Components used inside each page
- Component hierarchy (parent → child)
- One-line description for each component
```

---

## 7️⃣ Feature Code
```
Based on the project and tech stack I already provided,
build this specific feature:

Feature: [DESCRIBE THE FEATURE IN 1-2 LINES]

Write complete working code:
- Backend: API route + logic + DB query
- Frontend: UI + API call + state handling
Add comments so a beginner can understand each step.
```

---

## 8️⃣ Debugging
```
Based on the project and tech stack I already provided,
I have a bug in this feature: [DESCRIBE THE FEATURE]

Problem: [DESCRIBE THE BUG]

My Code:
[PASTE CODE HERE]

Error (if any):
[PASTE ERROR HERE]

Find the bug, explain why it happened, and give me the fixed code.
```

---

## 9️⃣ Testing
```
Based on the project and tech stack I already provided,
write complete test cases for this module:

Module: [NAME THE MODULE]

Code to test:
[PASTE CODE HERE]

Cover unit tests and edge cases with comments explaining each test.
```
