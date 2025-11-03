---
demo:
    title: 'Niagara Onsite Nov 2025'
---

[Back to Index](https://kensingtonschmidt.github.io/CopilotDemos1/)

# Niagara Onsite Nov 2025
## Search
Find the file you someone sent you last week that you don’t remember what it is called or where it is saved.

---
## Prompting
### GCSE in Action
#### Prompt 1
```text
Write a job description for a senior project manager
```
#### Prompt 2
```text
Generate a comprehensive job description for a senior project manager focused on technical project management for consumer electronic hardware. This role is urgent, and the candidate will join a dynamic team. Reference our company’s standard specs and industry norms. The description should be concise, max two pages, including responsibilities, qualifications.
```
### Extending the Prompt's Purpose
#### Prompt 1
> Anytime we use [] , please replace the object with something relevant from your environment and your work life.

```text
Recap the [/Contoso and Fabrikam Sustainability] meeting creating a table for action items, owners and due dates.
```
#### Prompt 2
```text
Write a follow up e-mail to the attendees of the /Contoso and Fabrikam Sustainability meeting with a table showing decisions made, another showing actions and owners and lastly a list of considerations for the next meeting
```
### Favorite example prompts for M365 Copilot
#### Chat with GPT-5
> Please make sure GPT-5 is Enabled for the following prompts

##### Prompt 1
```text
What are my top priorities today?
```
##### Prompt 2
```text
Analyze my calendar for conflicts and recommend how to resolve each conflict
```
##### Prompt 3
```text
Based on prior interactions I’ve had with [/person], give me 5 things that will be top of mind for our next interaction
```
##### Prompt 4
```text
Identify all tasks or action items assigned to me from my manager in this week’s emails, Teams chats, and meeting notes, and compile them into a checklist with due dates.
```
##### Prompt 5
```text
Help me identify colleagues with expertise in [topic]. Summarize their current role, key skills, and how their experience aligns with this topic.
```
##### Prompt 6
```text
Create a 360-degree overview of [customer] for an upcoming meeting based on recent emails, meetings, and status report, along with recent company news. Share recommendations for the meeting and potential questions I should ask. 
```
#### Researcher
> Open M365copilot.com in a web browser and run this prompt. Run each subsequent prompt in a new tab in your browser.

##### Prompt 1
```text
Based on the internal meeting discussion on [topic], draft a comprehensive research report evaluating the ideas proposed. Incorporate relevant insights from external market research, customer meetings and internal intelligence.
```
##### Prompt 2
```text
Create an action item tracker based on all communication channels and other information you can find from the past 7 days. Split it into two categories - actions pending on me, sorted by urgency (and relevance) and actions that I have asked others to do, categorized by if they have a follow up or not, and how long has it been since my request. Recommend who I need to follow up with or send a reminder to. 
```
#### Analyst
> Open M365copilot.com in a web browser and use the file Zava Sales Data.xlsx sent to you.
  
``` text
I need help answering the following 10 sales insights questions. Create a 2-column table with the question & response, and use [/Zava Sales Data.xlsx]. Here are the questions: 1. What are the top 3 products by total sales, and how do their profit margins compare? 2. Which country generated the highest sales, and what was its average discount rate? 3. How did the sales and profit for the product “Paseo” trend month-over-month in 2024? 4. What is the weighted average selling price (ASP) for each product group, and which group has the highest ASP? 5. Which customer segment achieved the highest average profit per unit sold? 6. What was the best and worst month for total sales, and what were the main drivers? 7. How does the gross margin % for “Paseo” compare to other products in the same segment? 8. What is the share of total sales and units for “Paseo” compared to all products? 9. Which segment had the highest average discount %, and how did that impact their profit? 10. Are there any segments or countries with negative profit or margin, and what’s causing it?
```
Feel free to reference the second excel spreadsheet called Zava Sales data validation.xslx to check your answers. How long would it have taken you to do this manually?

---
## Notebooks
> Use all of the Zava Sales Org QBR Word files sent to you

1. Create a new notebook called "Quarterly Business Reports" and add the 6 files.
2. Use the following prompt:
    ```text
    Create a chart showing our revenue growth and profit margins from FY24Q2 to FY25Q2 and include a list of the top 5 business outcomes for an annual report.    
    ```
3. Go back to the main page for the Quarterly Business Review notebook.
4. Select "Get audio overview" and then click Generate audio.
5. Select your style preferences. Add any specific instructions you would like
---
## Create
> Open M365copilot.com in a web browser and use the file Zava Sales Data.xlsx sent to you.
  
1. Click on Infographic.
2. Notice your options around orientation and brand kits. Use the following prompt:
   ```text
   Create an infographic showing the most popular flavors of water
   ```
3. Edit the suggested text as desired. Run the creation process and view the result.
---
## Copilot in the flow of work with the M365 Apps
Your researcher prompts should now be completed. Go take a look.
1. Open the results of the first researcher prompt with the research report on the topic you chose.
2. Click edit in pages.
3. You want help from a colleague on a portion of this. @mention someone sitting next to you. Make sure you click on their name to allow access.
4. Open the pages in Word.
5. Save the word document as "Research Report on [Your Topic]" to your OneDrive.
6. Open Powerpoint and select "Create a presentation with Copilot"
7. Use the following prompt:
 ```text
Create an executive summary presentation for the board on the research from [/Research Report on [Your topic]].
```
8. Select the 'Creative' style.
9. View the length options and select your preference.
10. Run the prompt and view the results.




---

1. In the **describe what you’d like to write** prompt box, type the following:

    ```text
    Using the Contoso [/CipherGuard Product Specification.docx] and the 'Project Implementation Plan' template provided in [paste in link to Project_Implementation_Plan.docx], draft a comprehensive project implementation plan for deploying Contoso CipherGuard. Ensure the plan aligns with the product specifications and follows the structure outlined in the template.
    ```

    > **NOTE:** Brackets indicate that a document is being referenced.
    > 1. CipherGuard Product Specification.docx = [Contoso_CipherGuard_Product_Specification.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_CipherGuard_Product_Specification.docx)
    > 1. Project Implementation Plan.docx = Use the link copied in the previous demo.
    > When referencing a document, you can paste the link directly or reference the file name if it is available in your OneDrive.

1. Select **Keep it** or, if time permits, demonstrate how to tweak the document using Copilot.

1. Once finished, save the document as **Contoso_Project_Plan.docx** and copy the shared URL (enable AutoSave and select your OneDrive account if prompted).

    ![Share link.](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

### Copilot in PowerPoint

We'll now use Copilot to generate a PowerPoint presentation based on the new proposal to implement the Contoso CipherGuard product.

1. Launch Microsoft PowerPoint from your browser [PowerPoint.new](https://PowerPoint.new) or use the desktop application.

1. Open a new blank presentation.

1. In the Copilot pane, select the "Create presentation from file" prompt.

1. Paste the shared link for the **Contoso_Project_Plan.docx** document and select **Send**.

    The full prompt should look like:

    ```text
    Create a presentation from [Link to Contoso_Project_Plan.docx].
    ```

1. Copilot begins generating slides based on the project plan, providing an outline along with features like speaker notes, images, slide layouts, and a General sensitivity label.

    > **NOTE:** Generating slides may take up to two minutes, depending on the document’s complexity and number of slides.

[Back to Index](https://emontes07.github.io/Learning/)
