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

## Architecture creation prompt.
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
