---
task:
    title: 'Copilot Chats'
---

## Copilot Chat  

Enhance decision-making by gathering insights, conducting online analysis, and drafting professional communications.  

You'll perform three tasks:  

- Research information using **Copilot Chat** (and optionally try GPT-5 for comparison).  
- Conduct an analysis using **Copilot Chat**.  
- Draft a professional communication using **Copilot in Word**.  

> **NOTE:** Sample prompts are provided to help you get started. Feel free to personalize them to suit your needs—be creative and explore! If Copilot Chat doesn’t deliver the result you want, refine your prompt and try again. Enjoy the process and have fun experimenting!  

---

### Task 1: Perform Online Research & Analysis  

Using **Copilot Chat**, gather insights on relevant topics by analyzing internal sources such as emails, chat history, and SharePoint documentation. Then, broaden your research with industry articles, external reports, or relevant websites.  

If you don't have a specific topic to research, focus on gathering insights from publicly available sources on a topic of your choice, such as **technology trends, market insights, customer experience, or compliance requirements.**  

**Steps**:

- Open a new browser tab and navigate to [M365copilot.com](https://m365copilot.com/)
- Select the Researcher agent or "@mention" the agent in chat
  
    ![screenshot showing work mode tab.](../Prompts/Media/Task1.png)  

**Sample Prompt** *(if no internal topic is available)*:

```text
Provide a comprehensive regional update for [Michigan] to assist in planning store operations. 
The update should include the latest news and insights on the following aspects:

Demographic Trends:
- Population growth or decline
- Age distribution
- Income levels
- Consumer behavior patterns

Financial Events:
- Economic indicators (e.g., employment rates, inflation, GDP growth)
- Major business developments (e.g., new businesses opening, closures, expansions)
- Changes in consumer spending habits

Weather Events:
- Current weather conditions and forecasts
- Recent and upcoming severe weather events (e.g., storms, hurricanes, heatwaves)
- Impact of weather on local infrastructure and transportation

Please provide detailed information and relevant data sources for each aspect to support strategic decision-making for store operations.
```

> **TIP:**  If the first response is too broad or too shallow, refine your prompt by adding more context (e.g., specific region, industry, or time frame).

> **Learning Outcome:**
After completing this task, you'll be able to use Copilot Chat to perform structured online research and gather actionable insights.

---

### Task 2: Summarize & Structure Meeting Notes  

Using **Copilot Chat**, transform raw meeting notes into a structured, professional summary. This will help you clearly communicate key decisions, action items, and responsibilities, ensuring alignment across teams.  

If you don’t have internal meeting notes available, you can use a sample transcript or text file that contains general meeting content for practice.  

**Steps**:

- Open a new browser tab and navigate to [M365copilot.com](https://m365copilot.com/)
- Select Copilot Chat
- Upload your meeting notes transcript (text file)
  
    ![screenshot showing meeting notes recap prompt.](../Prompts/Media/Task2.png)  

**Sample Prompt** *(after uploading meeting notes)*:

```text
Using my meeting notes, create a formal meeting notes structure and align the content with a meeting title that encapsulates the meeting goal or agenda. 

The final output should format my notes with these sections:
- Title  
- Attendees  
- Goal  
- Topics to Discuss  
- Product Details  
- Tasks to be Completed  
- Timelines and Responsibilities  
- Resources  
- Q&A and Next Steps
```

> **NOTE:** You can ask Copilot to adjust the level of detail (e.g., “make the summary more concise” or “expand on tasks to be completed”).

> **Learning Outcome:**
After completing this task, you'll know how to turn unstructured notes into a professional, shareable meeting summary.

---

### Task 3: Refine Results with Follow-Up Questions  

Using **Copilot Chat**, practice enhancing your results by asking follow-up questions. This task shows how you can go beyond the first answer, structure the data, and get actionable insights for decision-making.  

**Steps**:

- Open a new browser tab and navigate to [M365copilot.com](https://m365copilot.com/)
- Select Copilot Chat
- Enter the following series of prompts to progressively refine your research results:
  
    ![screenshot showing iterative follow-up questions.](../Prompts/Media/Task3.png)  

**Sample Prompt Sequence**:

```text
Please identify trends in consumer preferences for grocery markets and use these insights to develop ideas for new products for our grocery market chain.
```

```text
Please structure those ideas in a table format and for each idea add a column for the potential target groups and ideas for an advertising campaign.
```

```text
How can I prioritize these ideas effectively?
```

> **TIP:**  Follow-up questions help refine and upscale your results. Try clarifying prompts like: “Expand the table with additional product ideas based on recent market trends,” “Which ideas might have the highest ROI in the next 12 months?,” or “Create a prioritization matrix ranking these ideas by market demand, profitability, and alignment with brand values.”

> **Learning Outcome:**
After completing this task, you’ll understand how to use follow-up prompts to get richer insights and actionable recommendations from Copilot Chat.


### Task 4: Analyze Reviews & Visualize Sentiments  

Use **Copilot Chat** to transform raw survey or review data into actionable insights with charts and dashboards. You'll use a `.csv` file exported from Excel and ask Copilot to identify sentiment, uncover key themes, and generate visuals like a pie chart and word cloud.  

This task is perfect for analyzing customer feedback or product reviews and creating compelling visuals for presentations or reports.  

**Steps**:  

1. Save the following Excel notebook (right click "Save Link as").
- [Charger Reviews.csv](https://github.com/emontes07/Learning/blob/main/ResourceFiles/Charger%20Reviews.csv)
3. Save the selected worksheet as a `.csv` file.  
4. Open a new browser tab and navigate to [M365copilot.com](https://m365copilot.com/)  
5. Select Copilot Chat and upload your `.csv` file  
6. Use the following sample prompt to analyze and visualize the data.  

![screenshot showing sentiment analysis pie chart and word cloud](../Prompts/Media/Task4.png)  

**Sample Prompt** *(after uploading your CSV file)*:

```text
For each review, analyze the whole sentence and provide a sentiment analysis.  
List the top 10 sentiments with counts based on reviews using the attached file. Analyze the column “Reviews” located in column C.

Then, list the sentiment with counts on reviews and the top 10 themes in the reviews.  
Create a pie graph with Easter-themed colors based on the sentiment count and then create a word cloud based on themes and mentions.
```


> **TIP:**  If you want to customize the visuals further, follow up with questions like: Can you provide a downloadable version of the word cloud? Can you generate a more vibrant color scheme for the pie chart? What software can I use to recreate these visuals manually?

> **Learning Outcome:** 
After completing this task, you’ll be able to analyze qualitative data from reviews or survey feedback, extract themes and sentiment, and create visual summaries with Copilot Chat.


### Task 5: Visualize Financial Data with Charts & Heat Maps  

Use **Copilot Chat** to create a variety of data visualizations from Excel data, such as **monthly trends**, **product sales**, and **revenue distribution**. In this task, you'll explore the charting capabilities of Copilot with structured sales data to uncover key insights.  

**Steps**:  

1. Open your Excel workbook and select one worksheet (only one tab at a time can be used).

- [EV Charger Demo.csv](https://github.com/emontes07/Learning/blob/main/ResourceFiles/EV%20Charger%20Demo%20(Original).csv)
   
3. Save the selected worksheet as a `.csv` file.  
4. Open a new browser tab and navigate to [M365copilot.com](https://m365copilot.com/)  
5. Select Copilot Chat and upload your `.csv` file  
6. Use the following sample prompt to analyze and visualize the data.  

![screenshot showing product, revenue, and sales channel chart visualizations](../Prompts/Media/Task5.png)  

**Sample Prompt** *(after uploading your CSV file)*:

```text
List the visual charts you can create from the sales data and then create those charts.  
```
```text
Create a Monthly Revenue Trend chart.  
```
```text
Create a "Units Sold Distribution by Sales Channel" pie chart.
```
```text
Create a "Total Revenue by Product" chart.  
```
```text
Create a heat map of the most purchased products without purchase dates.
```

> **TIP:** 
Once the visuals are generated, try these follow-up prompts to enhance your analysis: Can you add trendlines or highlight seasonal peaks in the revenue chart? What does the heat map reveal about customer preferences? Group sales by category and create a stacked bar chart.Export these charts as image files I can use in PowerPoint.

> **Learning Outcome:**
After completing this task, you’ll be able to transform numerical sales data into various visual formats using Copilot Chat—including line charts, pie charts, bar charts, and heat maps—empowering you to extract and present insights for better decision-making.


### Task 6: Perform Calculations from Excel Data  

Use **Copilot Chat** to perform calculations directly from Excel data—without needing formulas or pivot tables. In this task, you’ll calculate the **total revenue** and the **average sales revenue** from a provided spreadsheet and explore how to break down those results further.

This is a great use case for operations, finance, or business teams looking for fast insights without writing code or complex formulas.

**Steps**:  

1. Save the following Excel workbook (right click "Save Link as").  
   - [EV Charger Demo with Rev + Sales.xlsx](https://github.com/emontes07/Learning/blob/main/ResourceFiles/EV%20Charger%20Demo%20with%20Rev%20%2B%20Sales%20CSV.csv)
2. Open a new browser tab and navigate to [M365copilot.com](https://m365copilot.com/)  
3. Select Copilot Chat and upload your `.xlsx` file  
4. Use the following sample prompt to analyze and calculate values from the data  

![screenshot showing Excel table and Copilot revenue calculation](../Prompts/Media/Task6.png)  

**Sample Prompt** *(after uploading your Excel file)*:

```text
Calculate the total revenue and the average sales revenue.
```

> **TIP:** 
Once the results are shown, try these follow-up prompts to dig deeper:
> Can you break down the revenue sources by sales channel or product?
> What are the monthly or quarterly sales trends?
> Can you calculate revenue growth over time?

> **Learning Outcome:**
After completing this task, you’ll be able to use Copilot Chat to quickly calculate financial metrics like total and average revenue, and follow up with deeper questions to uncover trends or performance breakdowns in your Excel data.


### Task 7: Convert Files to Another Format  

Use **Copilot Chat** to convert files between formats quickly and easily. This task helps you explore supported conversion types—perfect when you need to standardize formats or extract data for analysis.  

**Steps**:  

1. Upload the file you want to convert to **Copilot Chat**.  
2. Ask Copilot Chat to convert it into your desired format.  

![screenshot showing a PDF converted to Word](../Prompts/Media/Task7.png)

**Sample Prompt**:  

```text
Convert this PDF to a Word document.
```
You can also request Copilot to perform other conversions such as:

Document Conversions:
    PDF to Word (DOCX)
    PDF to Excel (XLSX)
    PDF to Text (TXT)
    Word (DOCX) to PDF
    Excel (XLSX) to PDF
    Text (TXT) to PDF

Spreadsheet Conversions:
    CSV to Excel (XLSX)
    Excel (XLSX) to CSV
    CSV to JSON
    Excel (XLSX) to JSON

Image Conversions:
    Image to PDF (JPG, PNG, etc. to PDF)
    PDF to Image (PDF to JPG, PNG, etc.)

Presentation Conversions:
    PowerPoint (PPTX) to PDF
    PDF to PowerPoint (PPTX)

Other Conversions:
    Markdown (MD) to HTML
    HTML to Markdown (MD)

> **TIP:** 
Ask follow-up questions like:
> Can you extract tables from this PDF into Excel?
> Save this as a downloadable file.
> Combine multiple PDFs into one document.”

> **Learning Outcome:**
After completing this task, you’ll know how to use Copilot Chat to convert files into various formats, making it easier to prepare data, create editable documents, and streamline workflows.
