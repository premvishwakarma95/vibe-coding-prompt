# vibe-coding-prompt

## First prompt to create prompt so i can give it to LLM or (Vibe coding tool).
So i am about to create new project using your model with wipe coding 
Project requirement (HR management system)
so i will explain you the project requirement
Project is HR can post hiring posts so there would be one role table and one department table in role we will define authorization and department so for now there would be only one deperatement and Role that's HR so for now we will create login and register api for now there would be only one account And after login we will have dash then there would be another section in sidebar called Posts here HR can create posts so post create is like we will also have another sidebar option called connectors in that hr will connect linkedin and other connector like email something so when hr create post then hr will select connectors means where she want to share this post so in post section we will show all the post she can update delete and read all the things that will also happen in connections like for now we will use only linkedin but after that we can use many more so this is Posts section.
Now i will explain you the connectors section so we will integrate connectors with the help of https://composio.dev/ here we will manage connectors use can see all his connectors or reconnect.

Now main part 
If any user will apply like apply in email that we have shared in the post then we will create the user in candidate table in our database and then analyze his or her resume according to posts requirement and then llm will rate out of 100% and store that rate and in new table wiht post id and candidate id table name you can say applications and if email is exist then don't create duplicate candidate just create application.

if hr click on any post then redirect to applications page and show only that post related application. and if hr click on any candidate then redirect to application and show all application of that candidate 

And use standard file system

---

## 1️⃣ Folder Structure
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

---

## 2️⃣ Database Schema
You are a senior backend developer.

My Project:
[DESCRIBE YOUR PROJECT IN 2-5 LINES]

My Database: [e.g. PostgreSQL, MongoDB]

Generate a complete database schema:
- All tables/collections with field names and data types
- Primary keys, foreign keys, and relations
- Add a one-line comment on each table explaining its purpose
Keep it simple and beginner-friendly.

---

## 3️⃣ API Design
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

---

## 4️⃣ Authentication Flow
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

---

## 5️⃣ Frontend Components
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

---

## 6️⃣ Feature Code
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

## 7️⃣ Debugging
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

---

## 8️⃣ Testing
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

---

## 9️⃣ Documentation
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
