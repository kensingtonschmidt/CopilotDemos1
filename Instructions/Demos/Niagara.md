---
demo:
    title: 'Niagara Onsite Nov 2025'
---

[Back to Index](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# Niagara Onsite Nov 2025
## Search

## Prompting
### GCSE in Action
Prompt 1
```text
Write a job description for a senior project manager
```
Prompt 2
```text
Generate a comprehensive job description for a senior project manager focused on technical project management for consumer electronic hardware. This role is urgent, and the candidate will join a dynamic team. Reference our company’s standard specs and industry norms. The description should be concise, max two pages, including responsibilities, qualifications.
```
### Extending the Prompt's Purpose
Prompt 1
> **Note:** Anytime we use [] , please replace the object with something relevant from your environment and your work life. 
```text
Recap the [/Contoso and Fabrikam Sustainability] meeting creating a table for action items, owners and due dates.
```
```text
Write a follow up e-mail to the attendees of the /Contoso and Fabrikam Sustainability meeting with a table showing decisions made, another showing actions and owners and lastly a list of considerations for the next meeting
```
### Top 10 example prompts for M365 Copilot
> **Note:** Please make sure GPT-5 is Enabled for the following prompts
```text
What are my top priorities today?
```
```text
Analyze my calendar for conflicts and recommend how to resolve each conflict
```
```text
Based on prior interactions I’ve had with [/person], give me 5 things that will be top of mind for our next interaction
```
```text
Identify all tasks or action items assigned to me from my manager in this week’s emails, Teams chats, and meeting notes, and compile them into a checklist with due dates.
```
```text
Help me identify colleagues with expertise in [topic]. Summarize their current role, key skills, and how their experience aligns with this topic.
```
```text
Create a 360-degree overview of [customer] for an upcoming meeting based on recent emails, meetings, and status report, along with recent company news. Share recommendations for the meeting and potential questions I should ask. 
```

The sample documents can be found in the MS-4021 GitHub repository [here](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles):

The specific files needed for this demo are:

- [Contoso_CipherGuard_Product_Specification.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_CipherGuard_Product_Specification.docx)

> **NOTE:** Allow up to 10 minutes for these files to sync to your OneDrive after downloading. To avoid delays during the demo, ensure these files are downloaded and available in your OneDrive well in advance. If the files are not available, open the documents and copy the shared file links to use in the demo.

## Demos

### Copilot Chat

Let’s start by asking Copilot to create a project implementation plan.

1. Open a browser and navigate to [M365copilot.com](https://m365copilot.com/).

1. Ensure Web mode is selected.

    ![screenshot showing web mode tab.](../Prompts/Media/web-mode.png)

1. In the prompt window, type the following:

    ```text
    You are an IT infrastructure manager at Contoso. Your task is to create a detailed project implementation plan for installing a new network security product in your corporate network. Your plan should include key milestones, resource allocation, potential risks, and a timeline to ensure successful deployment and minimal disruption to operations.
    ```

    > **NOTE:** Role-based prompts help Copilot understand the user's responsibilities and context, improving the relevance and specificity of the output.

1. Now we'll refine the project plan by asking Copilot to add new sections to the project plan:

    Input the following prompt:

    ```text
    Please add the following sections to the existing plan: testing and QA, training, communication, documentation and reporting, stakeholder analysis, project timeline, and risk assessment and mitigation. Ensure these sections provide detailed action steps and align with the existing content. Avoid duplicating any items already included in the original plan.
    ```

1. Lastly, have Copilot output the proposed project plan to a Word document:

    Input the following prompt:

    ```text
    Please export the project plan to a Word document.
    ```

1. Save the generated Word document as **Project_Implementation_Plan.docx**. Copy the shared URL from the document (enable AutoSave and select your OneDrive account if prompted).

    ![Share link.](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

### Copilot in Word

We'll now ask Copilot to expand on these strategies and draft proposals on how to implement them.

1. Open Word (either in your browser or desktop application).

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
