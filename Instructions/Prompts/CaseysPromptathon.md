---
task:
    title: 'Prompt-a-Thon Caseys'
---

# **Prompt-a-Thon: Casey’s Edition**

Welcome to the Prompt-a-Thon! This interactive session is designed to help you unlock the full potential of Microsoft Copilot by mastering the art and science of effective prompting. You’ll learn practical techniques to create clear, impactful prompts that drive real business value, save time, and boost productivity. Expect a hands-on, collaborative experience where you’ll experiment, iterate, and discover how Copilot can streamline your workflows and empower your team to achieve more.

---

## What You’ll Do

You’ll perform several tasks to build Copilot skills:

1. **Research & Analysis**: Use Copilot Chat to gather insights from internal and external sources.
2. **Summarize & Structure**: Transform raw meeting notes into professional summaries.
3. **Refine with Follow-Up**: Practice enhancing results by asking iterative questions.
4. **Recap Emails**: Use Copilot in Outlook to extract key actions from email threads.
5. **Analyze Reviews & Visualize Sentiments**: Turn survey or review data into actionable insights and visuals.
6. **Visualize Financial Data**: Create charts and heat maps from sales data.

---

## Prompting Framework: GCSE

To get the best results from Copilot, use the GCSE framework: 

![Effective Prompt.](../Prompts/Media/Prompt%2001.png)  

- **Goal**: What do you want Copilot to do?
- **Context**: Why do you need it? Who is involved?
- **Source**: What information or samples should Copilot use?
- **Expectations**: How should Copilot respond? (Format, tone, detail)

**TIP:** If your prompt is too short, you’ll get generic results. If it’s too long, Copilot might miss instructions. Aim for clarity and specificity.

---

## Guided Exercise #1: Perform Online Research & Analysis

### Researcher: Build a Marketing Plan

> **IMPORTANT:** Steps 1–4 should be completed at the beginning of the training (as indicated by slide 5) to give Researcher enough time to complete the first prompt.

1. Open **Researcher** from the left navigation in the Copilot app.  

    ![Screenshot showing Researcher selected in M365 Copilot menu.](../Prompts/Media/researcher.png)  

2. Enter the following prompt:

    ```text
    You are the Casey’s U.S. Retail & Foodservice Research Agent (model ‘o’). Ingest the two attached files, then incorporate the latest U.S. convenience and holiday retail data (NACS, NRF, Adobe Digital Economy Index), 2024 shopper trends (mobile ordering, loyalty engagement, sustainable packaging, social commerce), and competitive activations (7-Eleven, Kwik Trip, Circle K). Deliver a concise analysis identifying 2–3 emerging trends or gaps in Casey’s current holiday plan—such as missed mobile-first, loyalty, or social opportunities—and recommend actionable shifts (e.g., in-app bundles, fuel-plus-food rewards, or AR holiday engagement).

    Use clustering, correlation, and forecasting as needed. Include two brief visualizations (trend adoption rates and projected lift from recommendations) and suggest revised SMART KPIs aligned to 2024 benchmarks (e.g., +15% app order frequency). Conclude with a one-slide executive summary highlighting top opportunities and expected business impact.
    ```

If you have any supporting reference files, attach them using `/` (for example, **/Caseys Holiday Marketing Plan.docx** or **/Retail Trends 2024.xlsx).** This allows Copilot to use those documents as context.
For this specific scenario, we don’t have any supporting files to attach — simply run the prompt as-is.


3. Click **Submit**.  

Researcher will:  

- Combine insights from both internal files and the web.  
- Structure a marketing plan with recommendations on channels and content strategy.  
- Cite sources so you can validate its work.  

> **Note:** Researcher shows its reasoning path (“chain of thought”), and can call other agents when needed.  


## Analyst: Customer Segmentation & Financial Modeling

1. Open **Analyst** from the left navigation in the Copilot app.  

    ![Screenshot showing Analyst selected in M365 Copilot menu.](../Prompts/Media/Analyst.png)

2. Enter the following prompt:

    ```text
    Load the attached files. Produce a table of total Spend, Impressions, Clicks, Conversions, CTR, Conversion Rate, and ROAS, broken out first by Campaign and then by Channel. Provide a concise narrative summarizing the top‐level trends you observe (e.g., which campaign had the highest overall ROI, which channel drove the most impressions
    ```

3. Attach the file using **+**:  

   - **Caseys_Marketing_Campaign_Results.xlsx**  

    ![Screenshot showing attach files in Analyst.](../Prompts/Media/Analyst-attach-files.png)


Download the following file by right-clicking the link, selecting 'Save Link As,' and saving it to your local drive:
- [Caseys_Marketing_Campaign_Results](https://github.com/emontes07/Learning/blob/main/ResourceFiles/Caseys_Marketing_Campaign_Results.csv)


4. Click **Submit**.  

Analyst will:  

- Analyze the dataset.  
- Identify high-value customer segments.  
- Provide visualizations to back up recommendations.  

### Additional Analyst Scenarios

You can run these additional prompts for variety. Each follows the same pattern: **Prompt → Attach file → Submit → Review results.** But you don't have to attach the file again if you will be using the same input data.

- **Budget Reallocation Scenario & Projection**  

    ```text
    Based on historical ROI per channel and demographic segment, simulate a budget reallocation: shift 20% of spend away from the bottom-performing channel(s) into the top-performing one(s) while keeping total budget constant. Project the estimated change in total Conversions and overall ROAS under this new allocation, and present side-by-side charts of “Before vs. After.”    
    ```  

- **Audience Segment Analysis**  

    ```text
    Segment the data by Age Group and Gender. For each segment, calculate Conversion Rate, Cost per Conversion, and overall ROI. Rank segments by ROI and recommend the top 5 segments where Ross Stores should double down, and the bottom 5 to deprioritize, with supporting charts (e.g., bar-charts of ROI by segment).
    ```  

- **Campaign Performance**  

    ```text
    Analyze and visualize how the marketing campaign performed across each target segment 
    and help me decide where to re-target our next campaign.
    ```  


## Key Takeaway

- **Researcher**: accelerates strategy and planning with high-quality research.  
- **Analyst**: delivers data-driven insights with advanced analysis and visualizations.  

Together, Researcher and Analyst shorten the path from **question to insight**—turning weeks of effort into minutes.  

---

## **Guided Excercise #2**

## Create your first Agent

Discover how Microsoft 365 Copilot and Copilot Studio can help you solve everyday productivity challenges by designing a simple **retrieval-based agent**. This streamlined exercise will walk you through identifying a common issue, exploring how AI could help, and then creating a simple agent to test.  

You'll perform three tasks:

- Identify a productivity pain point  
- Explore how AI could help with retrieval and organization  
- Build and test a simple agent in **Copilot Studio**  

> **NOTE:** Sample prompts are provided to help you get started—feel free to personalize them to fit your situation.  
>
> If you’d like help generating or refining prompts, try the <a href="https://appsource.microsoft.com/en-us/product/office/WA200007578" target="_blank">Prompt Coach agent</a>, which can suggest, improve, and evaluate prompts so you get better results with Copilot.

### Task 1: Identify a Productivity Challenge  

Think about a common issue in your day-to-day work—something that slows you down or makes it harder to find or organize information. You can reflect individually, or use **Copilot Chat** as a partner to help generate ideas and surface common pain points.

Examples:

- Finding the latest version of a document  
- Gathering updates from multiple emails or chats  
- Remembering details from past projects or meetings  

**Steps:**  

- Open a new browser tab and navigate to [m365.cloud.microsoft/chat](https://m365.cloud.microsoft/chat). 

- Ensure the **Work mode** tab is selected in **Copilot Chat**.  

   ![Screenshot showing Work mode tab in Copilot Chat.](../Prompts/Media/work-mode.png)  

    **Sample Prompt:**

    ```text
    Summarize the top challenges I face in my daily work, based on recent emails, chats, and documents. Show results in a simple list with: 
    
    - Title (short label for the issue) 
    - Description (1–2 sentences) 
    ```  

### Task 2: Explore AI Solution Ideas with Researcher  

Use the **Researcher Agent** to explore how Copilot or agents might help with your chosen challenge.

**Steps:**  

- In the Copilot Chat menu, expand **Agents** and select **Researcher**.  

   ![Screenshot showing Researcher selected in M365 Copilot menu.](../Prompts/Media/researcher.png)  

- Try a sample prompt like this:  

   ```text
   Explore possible AI solutions to help with [insert productivity issue]. Focus on retrieval-based approaches using Microsoft Copilot or Copilot Studio agents. Summarize two or three ways an agent could help me find, organize, or summarize information more efficiently.
   ```  

    > **TIP:** Keep the focus on practical, everyday use cases—like quickly surfacing a doc or pulling updates from multiple sources.
  
    > **NOTE:** Researcher may take 5–10 minutes to complete, depending on your request. Its responses are highly detailed, so while it’s working, try running the same prompt in Copilot Chat. Comparing the two outputs is a great way to see how each tool approaches the task.
    
### Task 3: Build and Test Your Agent  

Now, create a simple retrieval agent in **Copilot Studio** to address your challenge.  

**Steps:**  

1. In the **Copilot Chat** menu, select **Create agent**.

   ![Screenshot showing create an agent link.](../Prompts/Media/create-agent.png)  

1. In the **Describe** tab, draft your agent’s role. For example:  

   ```text
   You’re a virtual assistant that helps me with [key task]. Be concise and always reference my recent files or resources when possible.
   ```  

   ![Screenshot showing describe agent with sample prompt filled in.](../Prompts/Media/create-agent-through-describe.png)  

1. Select the **Configure** Tab and add one knowledge source (e.g., **My Emails** or **My Teams chats and meetings**).

    ![Screenshot showing knowledge sources section in agent builder.](../Prompts/Media/knowledge-sources.png)

1. Test your agent using the **Test** pane and refine as needed.  
1. Select **Create** to publish your agent and start using it.  

> **TIP:** Even a very simple agent—like one that helps you find recent project files—can show the power of retrieval in your daily work.

## **Guided Excercise #3**

# Business Problem & Solution

Casey’s is growing fast, but customers struggle to find answers quickly on their public website. Job seekers want details on careers and benefits, communities need info on donations and grants, and customers look for EV charging, gift cards, and store locations. Partners also need easy access to corporate and real estate opportunities.

Right now, this information is scattered across multiple pages, creating frustration and missed engagement.

**Solution:**  
A virtual assistant that:
- Answers questions about careers, community programs, and products & services.
- Helps users find store locations, EV charging info, and gift card details.
- Shares corporate and real estate opportunities.
- Maintains a friendly, helpful tone to guide users to the right resources.

This assistant will streamline access, improve customer experience, and strengthen Casey’s brand.

---

# Step-by-Step Guide to Create the Agent

## Step 1: Access Copilot Studio

Open a new browser tab and navigate to m365.cloud.microsoft/chat (or however you usually navigate to Copilot).

## Step 2: Create a New Agent

Click “Create New Agent”.

Find the “Configure Toggle”.

![Effective Prompt.](../Prompts/Media/Caseys100.png)  

You’ll see fields for Name, Description, and Instructions. You will be inputting this information in Steps 3-5; examples are provided below.

## Step 3: Name Your Agent

Enter:  
**Name:** Casey’s Assistant

## Step 4: Add Description

**Example:**  
Casey’s Assistant helps customers find store locations, check promotions, and place online orders quickly and easily.

## Step 5: Write Instructions

**Example:**  

**Purpose:** Assist customers with store info, promotions, and online ordering.

**Capabilities:**
1. Answer questions about:
   - Careers (store positions, benefits, life at Casey’s)
   - Community programs (donations, fundraising, grants)
   - Products & services (pizza & fresh food, fuels, EV charging, gift cards)
   - Corporate info (about us, investor relations, real estate opportunities)
2. Provide links to relevant Casey’s pages when possible.
3. Avoid discussing online orders or transactions.
4. Always confirm user intent before sharing details.
5. Never share personal data or sensitive info.

![Effective Prompt.](../Prompts/Media/Caseys101.png)  

## Step 6: Insert Knowledge Source

Insert https://www.caseys.com/ into the knowledge source.

![Effective Prompt.](../Prompts/Media/Caseys102.png)  

## Step 7: Add Starter Prompts

Go ahead and add some starter prompts; you can add up to 6.

![Effective Prompt.](../Prompts/Media/Caseys103.png)  

**Here are some suggestions:**

**Careers**
- What store positions are currently available near me?
- What makes “Life at Casey’s” different from other convenience stores?
- What benefits do Casey’s employees receive after 90 days?

**Community**
- How can I submit a donation request for my local nonprofit?
- Does Casey’s offer fundraising opportunities for schools or sports teams?
- What is the “Cash for Classrooms” grant program and how do I apply?

**Products & More**
- What are Casey’s most popular pizza and fresh food options?
- Where can I find Casey’s EV charging stations in [insert state]?
- Can I buy Casey’s gift cards online or only in-store?

**Corporate & Real Estate**
- How can I learn more about Casey’s real estate opportunities or selling my convenience store?

## Step 8: Test Pane

Test your agent on the right-hand side of the screen by asking it a question. You can use a starter prompt or type any question you can think of!

![Effective Prompt.](../Prompts/Media/Caseys104.png)  

## Step 9: Create Your Agent

Click create agent and congratulations on building the agent.

![Effective Prompt.](../Prompts/Media/Caseys105.png)  



# **Scenario Options**

This next section is designed to help you practice and deepen your prompting skills. You can choose to work with Copilot Agents—such as Analyst or Researcher—or use the Copilot Agent to address a real business process. We’ve provided a list of suggested scenarios to inspire you, but if you have a specific challenge or workflow in mind, we highly encourage you to use your own. The goal is to apply what you’ve learned in a way that’s most relevant to your role and objectives.

## Choose a scenario to apply your prompting skills:

- **Scenario 1:** Organizational realignment—create a 60-day plan for a new leader.
- **Scenario 2:** Team performance—build a framework for tracking KPIs and supporting development.
- **Scenario 3:** Select your own business challenge and build an action plan.

> **TIP:** For inspiration, explore the Scenario Library: https://adoption.microsoft.com/en-us/scenario-library/

---

## Prompting Best Practices

- Break down complex tasks into manageable steps.
- Use persona-based prompting for specialized guidance.
- Ask Copilot what information it needs for success.
- Take a holistic approach—consider entire processes, not just tasks.
- Be curious and experiment with prompt structures.
- Test and refine your prompts for better results.

---

## Get Started

Partner with us to build a business case, explore pre-built agents, and keep up with Copilot news on WorkLab: https://www.microsoft.com/en-us/worklab/ai-at-work/
