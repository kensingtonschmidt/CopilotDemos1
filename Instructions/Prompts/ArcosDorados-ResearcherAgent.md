---
demo:
    title: 'Researcher and Analyst Demo'
---

[Back to Index](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# Agente Analyst

Esta demostración destaca cómo usar el agente **Analyst**, este es un agente experto integrados en la aplicación Copilot. Analyst piensa como un científico de datos experto, capaz de realizar análisis avanzados de datos y ejecutar Python, incluso si no sabes programar.

- **Analyst** piensa como un científico de datos experto, capaz de realizar análisis avanzados de datos y ejecutar Python, incluso si no sabes programar.  

## Demo Setup

Para completar estas demostraciones, deberás descargar lo siguientes archivos que contiene todos los archivos y recursos necesarios.

- [Arcos Dorados Resumen Visual Campaña 2024](https://github.com/emontes07/Learning/blob/main/ResourceFiles/Arcos%20Dorados%20Resumen%20Visual%20%E2%80%93%20Campa%C3%B1a%20Familiar%202024.pptx)

- [Arcos Dorados - Planificación Campaña Familiar 2024](https://github.com/emontes07/Learning/blob/main/ResourceFiles/Arcos%20Dorados%20-%20Planificaci%C3%B3n%20Campa%C3%B1a%20Familiar%202024.docx)

> **CONSEJO:** Antes de realizar la demostración, puedes almacenar los archivos en un sitio de SharePoint de tu entorno de pruebas para facilitar el acceso. Alternativamente, puedes guardar los archivos localmente y hacer referencia a ellos directamente en tus indicaciones usando **/**.


To access these agents:  

- Open the **Copilot app** from [m365.cloud.microsoft](https://m365.cloud.microsoft).  
- Use the **left navigation** to select **Researcher** or **Analyst**.  

> **Note:** You’ll need to point Researcher and Analyst to internal files (SharePoint/OneDrive) for grounded insights.

---

## Talking Points

- **Researcher** acts like a highly paid consultant: it can build structured, well-cited deliverables by blending internal files, competitor intelligence, and web sources.  
- **Analyst** is like having a data scientist on hand: it builds models, runs Python code, and visualizes trends instantly.  
- Both agents explain their reasoning transparently so you can validate results.  
- Together, they accelerate strategic work—marketing plans, customer segmentation, financial projections—so you can move faster with confidence.  

---

## Demo Steps

### Researcher: Build a Marketing Plan

> **IMPORTANT:** Steps 1–4 should be completed at the beginning of the training (as indicated by slide 5) to give Researcher enough time to complete the first prompt.

1. Open **Researcher** from the left navigation in the Copilot app.  

    ![Screenshot showing Researcher selected in M365 Copilot menu.](../Prompts/Media/researcher.png)  

1. Enter the following prompt:

    ```text
    Create a marketing plan for our newest SprintCycle EV charger launch. 
    Emphasize its AI-powered adaptive charging, modular design, and biometric access control. 
    Make sure to include recommendations on the right digital channels and content strategy. 
    Include insights from competitors and our past GTM campaigns.
    ```

1. Attach reference files using `/` (point to SharePoint/OneDrive):  

   - **/SprintCycle Charger Product Launch.docx**  
   - *(Optional)* **/Contoso - PedalPerks GTM Plan.docx**  

1. Click **Submit**.  

Researcher will:  

- Combine insights from both internal files and the web.  
- Structure a marketing plan with recommendations on channels and content strategy.  
- Cite sources so you can validate its work.  

> **Note:** Researcher shows its reasoning path (“chain of thought”), and can call other agents when needed.  

### Analyst: Customer Segmentation & Financial Modeling

1. Open **Analyst** from the left navigation in the Copilot app.  

    ![Screenshot showing Analyst selected in M365 Copilot menu.](../Prompts/Media/analyst.png)  

1. Enter the following prompt:

    ```text
    Find the right customer segment and demographic to sell our new EV charger, 
    include a graph to show how this will maximize our market opportunity.
    ```

1. Attach the file using **+**:  

   - **BoulderEV ebike Internal Market Forecast.xlsx**  

    ![Screenshot showing attach files in Analyst.](../Prompts/Media/Analyst-Attach-Files.png)  

1. Click **Submit**.  

Analyst will:  

- Analyze the dataset.  
- Identify high-value customer segments.  
- Provide visualizations to back up recommendations.  

### Additional Analyst Scenarios

You can run these additional prompts for variety. Each follows the same pattern: **Prompt → Attach file → Submit → Review results.**

- **Financial Projection**  

    ```text
    Build a 5-year financial projection from this data along with a graph to view revenue growth over time.
    ```  

    File: **BoulderEV ebike Internal Market Forecast.xlsx**  

- **Sales Performance**  

    ```text
    Analyze sales volume across locations to identify our highest and lowest performing stores, 
    along with a visualization of the best-selling products.
    ```  

    File: **BoulderEV ebike Internal Market Forecast.xlsx**  

- **Campaign Performance**  

    ```text
    Analyze and visualize how the marketing campaign performed across each target segment 
    and help me decide where to re-target our next campaign.
    ```  

    File: **BoulderEV ebike Internal Market Forecast.xlsx**  

## Key Takeaway

- **Researcher**: accelerates strategy and planning with high-quality research.  
- **Analyst**: delivers data-driven insights with advanced analysis and visualizations.  

Together, Researcher and Analyst shorten the path from **question to insight**—turning weeks of effort into minutes.  

[Back to Index](https://emontes07.github.io/Learning/)

