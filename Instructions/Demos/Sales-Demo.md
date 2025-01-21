---
demo:
    title: 'Sales Demo'
---

[Back to Index](https://microsoftlearning.github.io/Copilot-Immersion-Experience/)

# Sales Demo

**Scenario:**  
You're in sales for an EV charging company and are developing a strategic plan for the upcoming year.

## **Demo Setup**

The sample documents can be found in the MS-40XX GitHub repository [here](https://github.com/MicrosoftLearning/Copilot-Immersion-Experience/tree/master/ResourceFiles):

The specific files needed for this demo are:

- [Charger_sales_report_2022-2024.xlsx](https://github.com/MicrosoftLearning/Copilot-Immersion-Experience/raw/master/ResourceFiles/Charger_sales_report_2022-2024.xlsx)

> **NOTE:** It can take up to 10 minutes for these files to sync to your OneDrive once downloaded. It is advised that you download these files to your OneDrive account prior to delivering this demo. If the files are not available in your OneDrive, you can open the documents and copy the shared file links to use in the demo.

## Demo Steps

### **Step 1** (copilot Chat)

Let’s start by asking Copilot to research a key metric. In the **Copilot Chat** prompt field, input:

```text
What is the ratio of EV cars to EV chargers by region in the US for the past 3 years? Please show it in a table organized by region.
```

![Screenshot showing Copilot Chat EV charger Prompt.](../Demos/Media/copilot-chat-ev-charger-prompt.png)

### **Step 2** (Copilot Chat)

Now let’s compare national trends to your company’s sales performance. You’ll upload the provided dataset and ask Copilot to visualize the data:

1. In the prompt field, type:

   ```text
   I need to know the quarterly trends for each of our sales regions. Create a quarterly revenue line graph for the past 2 years based on:
   ```

1. Select **Add Content** and upload [**Charger_sales_report_2022-2024.xlsx**](https://github.com/MicrosoftLearning/Copilot-Immersion-Experience/raw/master/Resourcefiles/Charger_sales_report_2022-2024.xlsx).

    ![add content copilot chat.](../Demos/Media/add-content-copilot-chat.png)

### **Step 3** (Copilot Chat)

Let’s take it a step further by asking Copilot for recommendations exported to a word document:

1. After the graph is generated, input:

   ```text
   Based on the trend, suggest two ways I can increase EV charger sales in the Mountain and Midwest regions. Export the recommendations to a Word Document.
   ```

### **Step 4** (word)

Open the generated word document (Either in your browser or desktop application). We will now ask copilot to expand on these strategies and draft proposals on how to implement them.

1. Click anywhere in the body of the document and select the copilot icon. Type in the following prompt:

   ```text
   Draft a proposal on how we could implement each of the strategies outlined in this document
   ```

1. Select **Keep it** (or if you have some time, you can demonstrate tweaking the document using Copilot). Once finished save the document as **EV Sales Proposal.docx** and copy the Shared URL to be used in the next step. (You will have to enable autosave and select your OneDrive account)

    ![Share link.](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

### **Step 5** (PowerPoint)

1. Launch Microsoft PowerPoint from your browser [PowerPoint.new](https://PowerPoint.new) or use the desktop application.

1. Open a new blank presentation.

1. In the Copilot pane, select the "Create presentation from file" prompt.

1. Paste the **EV Sales Proposal.docx** link after "Create a presentation from" and select **Send**.

    The full prompt should look like:

    ```text
    Create a presentation from [Link to Product Concept.docx].
    ```

1. Copilot will begin generating slides based on the EV Sales Proposal, providing an outline along with features like speaker notes, images, slide layouts, and a General sensitivity label.

    > **NOTE:** Generating slides may take up to two minutes, depending on the document’s complexity and number of slides.

[Back to Index](https://microsoftlearning.github.io/Copilot-Immersion-Experience/)
