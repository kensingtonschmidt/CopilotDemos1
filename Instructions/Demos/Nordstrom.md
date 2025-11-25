---
demo:
    title: 'Nordstrom Onsite Dec 2025'
---

[Back to Index](https://kensingtonschmidt.github.io/CopilotDemos1/)

# Nordstrom Onsite - Hands on with M365 Copilot Nov 2025

## Reference Material
### Copilot Disambiguation
#### Main User Experiences or App
- **M365 Copilot** - name of the central app, experience, and license that enables the full, rich Copilot experience inside M365. It is accessed via the M365 Copilot app as well as in Word, Excel, PPT, Outlook, OneNote and other M365 apps. You are all licensed users in this training. Note: Some of the people you build agents for may end up not being licensed users.
-  **M365 Copilot Chat** - name of the free/included experience that **all** M365 users can access. Can reason over web data and can access agents you deploy.

#### Main Agent Authoring Tools
> Agents built with these tools can be published to M365 Copilot app, any M365 Copilot experience inside Word, Excel, PPT, Outlook, OneNote, etc. You can also use Copilot Studio Full to publish agents to many other channels (Ex: Web).

- **Copilot Studio Lite** - Built into M365 Copilot app directly as a quick, easy way to build declarative agents for business users and anyone else who wants to template a prompt to share.
- **Copilot Studio Full** - Main Low Code authoring tool for developers, IT Pros, and power users. (Access Copilot Studio Full here and bookmark)[http://copilotstudio.microsoft.com/]

#### When to use a prompt or build an agent?
- **M365 Copilot** - Microsoft's 'super agent' if you will. It has tremendous and ever expanding capabilities that can be unlocked with good prompting from a chat window in the M365 Copilot app or in the core M365 Apps themselves, such as Word, Excel, PPT, Outlook, OneNote and more.
  - Try prompt first with GCSE best practices
  - Try MS first party agents
  - Individual productivity work that gives me the most flexibility to be creative and research.
- **Copilot Studio Lite** - the built-in agent authoring tool inside of M365 Copilot itself.
  - When I want to 'templatize' my prompts for myself or my team.
  - When I want to narrow the scope to a specific set of data inside M365 or web to create better results
  - When I want to dictate the output to look a certain way or templatize it.
  - When I want to extend an agent with AgentIQ data to unlicensed users
- **Copilot Studio Full** - accessed via [http://copilotstudio.microsoft.com]. It is the core low-code authoring tool for developers, IT Pros, and power users.
  - All Copilot Studio Lite situations AND
  - When I want a company sanctioned agent that can be used by anybody in the org (ie larger possible scope to rollout than a Studio Lite agent)
  - When I want to use third party connectors to data sources
  - When I want an agent to be able to take an action
  - When I want to create a fully autonomous agent
  - When I want to use MCP or A2A capabilities
  - When I want to leverage and access models built in Azure AI Foundry

## Prep Work
> Copy all of the Word files and the Excel file provided to you in the Slack channel into a folder in your OneDrive.
> View (Anthropic Joins the Mulit-Modal Lineup in Microsoft Copilot Studio) [https://www.microsoft.com/en-us/microsoft-copilot/blog/copilot-studio/anthropic-joins-the-multi-model-lineup-in-microsoft-copilot-studio/]

## Top Advanced Prompts
### Favorite example prompts for M365 Copilot
#### Chat with GPT-5
> Please make sure GPT-5 is Enabled for the following prompts

##### 1. Priorities Prompt
```text
What are my top priorities today?
```
##### 2. Scheduling prompts
In the same chat window as Prompt 1, click on the three dots below the response and click "Schedule this prompt". 
##### 3. Calendar conflicts prompt  
```text
Analyze my calendar for conflicts and recommend how to resolve each conflict
```
##### 4. One on One Meeting prep prompt
```text
Based on prior interactions I’ve had with [/person], give me 5 things that will be top of mind for our next interaction
```
##### 5. Tasks from my manager prompt
```text
Identify all tasks or action items assigned to me from my manager in this week’s emails, Teams chats, and meeting notes, and compile them into a checklist with due dates.
```
##### 6. Find people with expertise prompt
```text
Help me identify colleagues with expertise in [topic]. Summarize their current role, key skills, and how their experience aligns with this topic.
```
##### 7. Customer overview prompt
```text
Create a 360-degree overview of [customer] for an upcoming meeting based on recent emails, meetings, and status report, along with recent company news. Share recommendations for the meeting and potential questions I should ask. 
```
#### Researcher
> Open M365copilot.com in a web browser and run this prompt. Run each subsequent prompt in a new tab in your browser.

##### 1. Research report on specific meeting topic prompt
```text
Based on the internal meeting discussion on [topic], draft a comprehensive research report evaluating the ideas proposed. Incorporate relevant insights from external market research, customer meetings and internal intelligence.
```
##### 2. Action item prompt with Researcher
```text
Create an action item tracker based on all communication channels and other information you can find from the past 7 days. Split it into two categories - actions pending on me, sorted by urgency (and relevance) and actions that I have asked others to do, categorized by if they have a follow up or not, and how long has it been since my request. Recommend who I need to follow up with or send a reminder to. 
```
#### Analyst
> Open M365copilot.com in a web browser and use the file Zava Sales Data.xlsx sent to you.

##### 1. Sales insights prompt
``` text
I need help answering the following 10 sales insights questions. Create a 2-column table with the question & response, and use [/Zava Sales Data.xlsx]. Here are the questions: 1. What are the top 3 products by total sales, and how do their profit margins compare? 2. Which country generated the highest sales, and what was its average discount rate? 3. How did the sales and profit for the product “Paseo” trend month-over-month in 2024? 4. What is the weighted average selling price (ASP) for each product group, and which group has the highest ASP? 5. Which customer segment achieved the highest average profit per unit sold? 6. What was the best and worst month for total sales, and what were the main drivers? 7. How does the gross margin % for “Paseo” compare to other products in the same segment? 8. What is the share of total sales and units for “Paseo” compared to all products? 9. Which segment had the highest average discount %, and how did that impact their profit? 10. Are there any segments or countries with negative profit or margin, and what’s causing it?
```
##### 2. Check your answers
Feel free to reference the second excel spreadsheet called Zava Sales data validation.xslx to check your answers. How long would it have taken you to do this manually?

---
##### Notebooks
> Use all of the Zava Sales Org QBR Word files sent to you

1. Create a new notebook called "Quarterly Business Reports" and add the 6 files by finding them in your OneDrive folder you created earlier.
2. Use the following prompt:
```text
Create a chart showing our revenue growth and profit margins from FY24Q2 to FY25Q2 and include a list of the top 5 business outcomes for an annual report.    
```
3. Go back to the main page for the Quarterly Business Review notebook.
4. Select "Get audio overview" and then click Generate audio.
5. Select your style preferences. Add any specific instructions you would like.

---
## Copilot in the flow of work with the M365 Apps
Your researcher prompts should now be completed. Go take a look.
1. Open the results of the first researcher prompt with the research report on the topic you chose.
2. Click edit in pages.
3. You want help from a colleague on a portion of this. @mention someone sitting next to you. Make sure you click on their name to allow access.
4. Open the pages in Word.
5. Save the word document as "Research Report on [Your Topic]" to your OneDrive.
6. Open Outlook.
7. Find a lengthy email chain and ask it to summarize.
8. Reply to the email thread using Copilot to help you draft by using "word vomit".
9. Find that same lengthy email chain and click the "Schedule with Copilot" button in New Outlook.

---
