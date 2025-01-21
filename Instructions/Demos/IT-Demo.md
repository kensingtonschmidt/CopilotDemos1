---
demo:
    title: 'IT Demo'
---

[Back to Index](https://microsoftlearning.github.io/Copilot-Immersion-Experience/)

# IT Demo

**Scenario:**  
As an IT Infrastructure Manager, you are planning to install a new network security product into your corporate network.

## **Demo Setup**

The sample documents can be found in the MS-40XX GitHub repository [here](https://github.com/MicrosoftLearning/Copilot-Immersion-Experience/tree/master/ResourceFiles):

The specific files needed for this demo are:

- [Contoso_CipherGuard_Product_Specification.docx](https://github.com/MicrosoftLearning/Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_CipherGuard_Product_Specification.docx)

> **NOTE:** It can take up to 10 minutes for these files to sync to your OneDrive once downloaded. It is advised that you download these files to your OneDrive account prior to delivering this demo. If the files are not available in your OneDrive, you can open the documents and copy the shared file links to use in the demo.

## Demo Steps

### **Step 1** (copilot Chat)

Let’s start by asking Copilot to create a project implementation plan. In the **Copilot Chat** prompt field, input (Taking advantage of Role based prompting):

    ```
    You are an IT infrastructure manager at Contoso. Your task is to create a detailed project implementation plan for installing a new network security product in your corporate network. Your plan should include key milestones, resource allocation, potential risks, and a timeline to ensure successful deployment and minimal disruption to operations.
    ```

### **Step 2** (Copilot Chat)

Now we will refine the project plan by asking Copilot to add new sections to the project plan:

    ```
    Please add the following sections to the existing plan: testing and QA, training, communication, documentation and reporting, stakeholder analysis, project timeline, and risk assessment and mitigation. Ensure these sections provide detailed action steps and align with the existing content. Avoid duplicating any items already included in the original plan.
    ```

### **Step 3** (Copilot Chat)

Have copilot output the proposed project plan to a Word document:

    ```
    Please export the project plan to a Word document.
    ```

Copy the Shared URL From this document (name it **Project_Implementation_Plan.docx**). (you will have to enable autosave)

![Share link.](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

### **Step 4** (word)

Open word (Either in your browser or desktop application). We will now ask copilot to expand on these strategies and draft proposals on how to implement them.

1. In the **describe what youd like to write** prompt box type the following:

        ```text
        Using the Contoso CipherGuard Product Specification.docx and the 'Project Implementation Plan' template provided in Project_Implementation_Plan.docx, draft a comprehensive project implementation plan for deploying Contoso CipherGuard. Ensure the plan aligns with the product specifications and follows the structure outlined in the template.
        ```

1. Select **Keep it** (or if you have some time, you can demonstrate tweaking the document using Copilot). Once finished save the document as **Contoso_Project_plan.docx** and copy the Shared URL. (you will have to enable autosave)

### **Step 5** (PowerPoint)

We will now use Copilot to generate a PowerPoint presentation based on the new proposal to implement the Contoso CipherGuard product.

1. Launch Microsoft PowerPoint from your browser [PowerPoint.new](https://PowerPoint.new) or use the desktop application.

1. Open a new blank presentation.

1. In the Copilot pane, select the "Create presentation from file" prompt.

1. Paste the **Contoso_Project_plan.docx** link after "Create a presentation from" and select **Send**.

    The full prompt should look like:

        ```text
        Create a presentation from [Link to Product Concept.docx].
        ```

1. Copilot will begin generating slides based on the EV Sales Proposal, providing an outline along with features like speaker notes, images, slide layouts, and a General sensitivity label.

    > [!NOTE]
    > Generating slides may take up to two minutes, depending on the document’s complexity and number of slides.

[Back to Index](https://microsoftlearning.github.io/Copilot-Immersion-Experience/)
