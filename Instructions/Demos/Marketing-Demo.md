---
demo:
    title: 'Marketing Demo'
---

[Back to Index](https://microsoftlearning.github.io/Copilot-Immersion-Experience/)

# Marketing Demo

**Scenario:**  
As the Marketing Director for Contoso Beverage, you will consolidate insights from multiple sources into a marketing analysis using Copilot Chat. Then, use Copilot in Excel to analyze sales data and extract key trends to inform your strategy

## Demo Setup

The sample documents can be found in the MS-40XX GitHub repository [here](https://github.com/MicrosoftLearning/Copilot-Immersion-Experience/tree/master/ResourceFiles):

The specific files needed for this demo are:

- [Promotion_Plan_for_Chai_Tea_in_Latin_America.docx](https://github.com/MicrosoftLearning/Copilot-Immersion-Experience/raw/master/ResourceFiles/Promotion_Plan_for_Chai_Tea_in_Latin_America.docx)

- [Mystic_Spice_Premium_Chai_Tea_product_description.docx](https://github.com/MicrosoftLearning/Copilot-Immersion-Experience/raw/master/ResourceFiles/Mystic_Spice_Premium_Chai_Tea_product_description.docx)

- [Contoso_Chai_Tea_market_trends_2023.xlsx](https://github.com/MicrosoftLearning/Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_Chai_Tea_market_trends_2023.xlsx)

> **NOTE:** Allow up to 10 minutes for these files to sync to your OneDrive after downloading. To avoid delays during the demo, ensure these files are downloaded and available in your OneDrive well in advance. If the files are not available, open the documents and copy the shared file links to use in the demo.

## Demos

### Copilot Chat

1. Open a browser and navigate to [M365copilot.com](https://m365copilot.com/).

1. Ensure Work mode is selected.

1. In the prompt window, type the following:

    ```text
    You are the LATAM Marketing Director for Contoso Beverage. Create a LATAM Market Analysis report for Mystic Spice Premium Chai Tea using the attached files. Include the product description, market trend analysis, and a promotion plan for Latin America.

    [Promotion_Plan_for_Chai_Tea_in_Latin_America.docx], [Mystic_Spice_Premium_Chai_Tea_product_description.docx], [Contoso_Chai_Tea_market_trends_2023.xlsx]

    ```

    > **NOTE:** Brackets indicate that a document is being referenced. When referencing a document, you can paste the shared link directly or reference the file name if it is available in your OneDrive.

1. Next you will Have Copilot perform a competitive analysis against other companies selling chai tea in LATAM:

    Input the following prompt:

    ```text
    This report looks good. Please add a section to the above output titled "Competitive Analysis." Include information on beverage companies in Latin America that sell Chai Tea, detailing their strengths, weaknesses, market share, and pricing strategies.
    ```

1. Lastly, have Copilot output the Market Analysis to a Word document:

    Input the following prompt:

    ```text
    Please export the Market Analysis to a Word document.
    ```

1. save this new document as **LATAM_Market_Analysis.docx**.

### Copilot in Word

Next we will review the Word document created in the previous. It looks good so far, but you want to add a section for a new social media campaign.

1. Open Word (either in your browser or desktop application).

1. Open the **LATAM_Market_Analysis.docx** document generated in the previous demo.

1. Click anywhere in the body at the bottom of the document and select the Copilot icon.

    Type in the following prompt:

    ```text
    Please add a new section titled 'The Spice of Life Social Media Campaign.' In this section, outline a campaign strategy that promotes Mystic Spice Premium Chai Tea on social media. Focus on key messaging, target audience, platforms to use, and sample post ideas.
    ```

1. Once Copilot is done generating the next section, select **Keep it** or, if time permits, demonstrate how to tweak the document using Copilot.

### Copilot in Excel

1. ensure you have downloaded [Contoso_Chai_Tea_market_trends_2023.xlsx](https://github.com/MicrosoftLearning/Copilot-Immersion-Experience/raw/master/Contoso_Chai_Tea_market_trends_2023.xlsx) and open the document in Excel (either on the web or desktop application).

1. Select **Copilot** from the ribbon to open the Copilot pane.

1. Type in the following prompt into Excel:

    ```text
    On average, how many sales do we get per social media campaign view?
    ```

1. Next, ask Copilot to compare sales to social media engagement:

    ```text
    Can you show a correlation between social media engagement and sales?
    ```

1. Next, Type in the following prompt:

    ```text
    How many social media campaign views did we have from September to December?
    ```
