# EX.NO.10-Creating-a-Custom-GPT-for-Saveetha-Engineering-College-using-OpenAI-s-GPT-Builder
## AIM
To understand the concept of a Custom GPT and to design, build, configure, and publish a Custom GPT chatbot for Saveetha Engineering College (www.saveetha.ac.in) using OpenAI's GPT Builder, so that it can answer student and visitor questions about the college's courses, admissions, fees, facilities, and placements.
## WHAT IS A CUSTOM GPT?
A Custom GPT is a personalised version of ChatGPT that can be built without writing any code. It is created by giving the GPT Builder three things: a name, a set of Instructions that describe how it should behave, and (optionally) reference files called Knowledge that it reads before answering. Once published, the Custom GPT behaves like a specialised chatbot — for example, a “Saveetha Engineering College Assistant” that always answers using the college's own information instead of general internet knowledge.
### TOOLS REQUIRED
•	Web browser – Google Chrome or Microsoft Edge 
•	A ChatGPT account with a Plus, Team, Enterprise, or Edu subscription (the GPT Builder is not available on the free plan)
•	OpenAI's GPT Builder – built into ChatGPT, opened from chatgpt.com/create
•	Reference material about Saveetha Engineering College, collected from www.saveetha.ac.in (About, Courses, Admission, Placement, and Contact pages)
•	MS Word / Google Docs – to organise the collected information into clean Knowledge files (PDF/DOCX) before uploading
•	(Optional) Canva or the built-in DALL·E image generator – to design a profile picture/logo for the GPT
## PROCEDURE
### Step 1: Collecting College Information (Knowledge Preparation)
Before building the GPT, gather accurate information about Saveetha Engineering College from its official website www.saveetha.ac.in. Visit and note down content from pages such as About Us, Departments/Courses Offered, Admission Procedure, Fee Structure, Placements, Facilities, and Contact Details. Paste this content into a Word document and save it as a PDF. This file becomes the “Knowledge” for the GPT, so that it answers only with correct, college-specific information instead of guessing.
### Step 2: Signing in to ChatGPT
Open a web browser and go to chatgpt.com. Sign in using an existing OpenAI account, or create a new one. Make sure the account is upgraded to a ChatGPT Plus, Team, Enterprise, or Edu plan, since the GPT Builder is a paid-plan feature and is not available on the free version.
### Step 3: Opening the GPT Builder
On the left sidebar, click “Explore GPTs” and then click the “+ Create” button (or go directly to chatgpt.com/create). This opens the GPT Builder, which has two tabs: Create and Configure.
### Step 4: Building the GPT Conversationally (Create Tab)
In the Create tab, type a plain-English description of the required GPT in the message box, for example:
“Create a GPT for Saveetha Engineering College that answers questions about admissions, courses, fees, placements, and campus facilities in a friendly and professional tone.”
The Builder chats back and automatically suggests a name, a short description, and a profile picture for the GPT based on this description.
### Step 5: Fine-Tuning with the Configure Tab
Switch to the Configure tab for full manual control over the GPT, and fill in the following fields:
•	Name: e.g., “Saveetha Engineering College Assistant”
•	Description: a one-line summary, e.g., “Your guide to admissions, courses, fees, and placements at Saveetha Engineering College.”
•	Instructions: a detailed system prompt describing the GPT's role, tone, and rules (see the sample instructions given later in this report).
•	Conversation starters: four sample questions users can click to begin the chat, for example:
1.	What B.Tech courses does Saveetha Engineering College offer?
2.	How do I apply for admission?
3.	What is the placement record of the college?
4.	Where is the campus located?
### Step 6: Uploading Knowledge Files
In the Knowledge section of the Configure tab, click “Upload files” and add the PDF/DOCX file prepared in Step 1. This lets the GPT search and quote from the actual college content instead of guessing, which keeps its answers accurate and trustworthy. As a best practice, upload 2 to 5 well-organised files rather than many small ones, since retrieval accuracy drops once too many files are added.
### Step 7: Enabling Capabilities
In the Capabilities section, select the tools the GPT is allowed to use:
•	Web Browsing – to fetch live information if the uploaded knowledge file becomes outdated
•	Code Interpreter & Data Analysis – not usually needed for a college-information bot, so it can be left off
•	Image Generation (DALL·E) – optional, for generating a campus or course-related illustration
For a simple college-information GPT, enabling Web Browsing along with the uploaded Knowledge is generally enough.
### Step 8: Setting Up Actions (Optional, Advanced)
Actions allow the GPT to call an external API — for example, to check live seat availability or fetch the latest fee notification from a college server. This requires an API endpoint and an OpenAPI schema, so it is optional for a basic informational GPT and can be skipped by beginners.
### Step 9: Testing the GPT
Use the Preview panel on the right side of the Builder to chat with the GPT before publishing it. Ask sample questions such as “What courses are offered?” or “How do I apply for admission?” and check whether the answers are correct, polite, and based on the uploaded knowledge. If any answer is wrong or incomplete, edit the Instructions or Knowledge files and test again until the responses are accurate.
### Step 10: Publishing and Sharing
Click the “Create” (or “Save”) button in the top-right corner of the Builder. Choose who can access the GPT:
•	Only me – for personal testing
•	Anyone with the link – to share with students and faculty of the department
•	GPT Store (Public) – to make the GPT visible to all ChatGPT users
Click “Publish”/“Update” to finish. Copy the generated link and share it with students through the college portal, WhatsApp group, or LMS.
### SAMPLE INSTRUCTIONS (SYSTEM PROMPT) FOR THE GPT
<br><img width="587" height="151" alt="image" src="https://github.com/user-attachments/assets/cd378cba-9488-4cc9-9974-99a44f3695f8" /></br>
## SAMPLE OUTPUT SCREEN
The screen below shows a sample conversation with the published “Saveetha Engineering College Assistant” Custom GPT, illustrating how it answers a student's admission query using the uploaded knowledge files.
</br><img width="545" height="385" alt="image" src="https://github.com/user-attachments/assets/677bee25-a510-48db-824d-4dbb5795d610" /></br>
## OUTPUT
A working Custom GPT named “Saveetha Engineering College Assistant” is created and published. When a user asks questions like “What courses does Saveetha offer?” or “How can I apply for B.Tech admission?”, the GPT replies with accurate information drawn from the uploaded college knowledge files, in a friendly and professional tone.
## RESULT
Thus, a Custom GPT chatbot for Saveetha Engineering College was successfully designed, configured with knowledge files and instructions, tested, and published using OpenAI's GPT
Builder.

## CONCLUSION

### In conclusion, building a Custom GPT shows how modern generative AI tools let anyone — even without programming knowledge — create a specialised, organisation-branded chatbot in a few simple steps. By combining clear instructions, focused knowledge files, and the right capabilities, Saveetha Engineering College can offer students and visitors instant, accurate answers to their questions, saving time for both the institution and its users.

