---
demo:
    title: 'Researcher and Analyst Demo'
---

[Back to Index](https://github.com/emontes07/Learning/)

# Agente Analyst

Esta demostración destaca cómo usar el agente **Analyst**, este es un agente experto integrados en la aplicación Copilot. Analyst piensa como un científico de datos experto, capaz de realizar análisis avanzados de datos y ejecutar Python, incluso si no sabes programar.

- **Analyst** piensa como un científico de datos experto, capaz de realizar análisis avanzados de datos y ejecutar Python, incluso si no sabes programar.  

**Tarea 1: Realizar investigación y análisis en línea**

Para completar estas demostraciones, deberás descargar lo siguientes archivos que contiene todos los archivos y recursos necesarios.

- [Arcos Dorados Resumen Visual Campaña 2024](https://github.com/emontes07/Learning/blob/main/ResourceFiles/Arcos%20Dorados%20Resumen%20Visual%20%E2%80%93%20Campa%C3%B1a%20Familiar%202024.pptx)

- [Arcos Dorados - Planificación Campaña Familiar 2024](https://github.com/emontes07/Learning/blob/main/ResourceFiles/Arcos%20Dorados%20-%20Planificaci%C3%B3n%20Campa%C3%B1a%20Familiar%202024.docx)

> **CONSEJO:** Antes de realizar la demostración, puedes almacenar los archivos en un sitio de SharePoint de tu entorno de pruebas para facilitar el acceso. Alternativamente, puedes guardar los archivos localmente y hacer referencia a ellos directamente en tus indicaciones usando **/**.



Para acceder a estos agentes:  

- Abre la **aplicación Copilot** desde [m365.cloud.microsoft](https://m365.cloud.microsoft).  
- Usa la **navegación del panel izquierdo** para seleccionar  **Analyst**.  

> **Nota:** Deberás vincular Researcher y Analyst a archivos internos (SharePoint/OneDrive) para obtener información fundamentada en datos confiables.

---

## Escenario
• El departamento de Marketing de Arcos Dorados está planificando la campaña de octubre 2025 en Ciudad de México.
• Para esta planeación, utilizarán el agente **Analyst** en Copilot.
• El agente ayudará a:
  – Investigar tendencias y comportamientos de consumo.
  – Proponer alianzas estratégicas para la Cajita Feliz.
  – Recomendar el tipo de juguetes más relevantes para la audiencia infantil.
• ¿Por qué usar Analyst?
  – Analiza datos de mercado de forma rápida y confiable.
  – Detecta oportunidades y brechas en la estrategia actual.
  – Visualiza el impacto estimado de cada recomendación.
  – Reduce riesgos al evitar decisiones basadas solo en intuición.

---

### Analyst: Construye un Plan de Marketing

> **IMPORTANTE:** Los pasos 1–4 deben completarse al inicio de la sesión de entrenamiento (como se indica en la diapositiva 5) para darle al agente **Analyst** suficiente tiempo para completar el primer prompt.

1. Abre **Analyst** desde la navegación izquierda en la aplicación de Copilot.  

    ![Captura de pantalla mostrando Analyst seleccionado en el menú de M365 Copilot.](../Prompts/Media/researcher.png)  

2. Ingresa el siguiente prompt:

    ```text
    Crea un plan de marketing para la próxima campaña de Cajita Feliz 
    durante el evento en Ciudad de México (24-26 octubre 2025). 
    Destaca posibles alianzas con franquicias infantiles, 
    recomienda el tipo de juguetes más atractivos para niños de 4 a 10 años 
    y sugiere la mezcla de canales más efectiva (TV, redes sociales, activaciones en restaurante). 
    Incluye aprendizajes de campañas pasadas y referencias de competidores como Burger King y KFC.
    ```

1. Adjunta los archivos de referencia usando `/` (apuntando a SharePoint/OneDrive):  

   - **/Arcos Dorados - Planificación Campaña Familiar 2024.docx**  
   - *(Opcional)* **/Arcos Dorados Resumen Visual – Campaña Familiar 2024.pptx**

    ![Screenshot showing attach files in Analyst.](../Prompts/Media/ArcosAnalyst01.png)  

2. Haz clic en **Enviar**.  

Analyst hará lo siguiente:  

- Combinará los hallazgos de los documentos internos con información del mercado y la web.  
- Estructurará un plan de marketing con recomendaciones sobre la mezcla de canales y la estrategia de contenidos.  
- Citará las fuentes para que puedas validar el análisis.  

> **Nota:** Analyst muestra su ruta de razonamiento (“chain of thought”) y puede invocar otros agentes si es necesario.  

### Analyst: Segmentación de Clientes y Modelado Financiero

1. Abre **Analyst** desde la navegación izquierda en la aplicación de Copilot.


    ![Captura de pantalla mostrando Analyst seleccionado en el menú de M365 Copilot.](../Prompts/Media/researcher.png)  

1. Ingresa el siguiente prompt:

```text
Genera un gráfico de barras que muestre la preferencia de tipo de juguetes 
para niños de 4 a 10 años, comparando 2024 vs. 2025. 
Clasifica por categoría (por ejemplo: personajes de películas, juguetes educativos, 
juegos de mesa, juguetes de realidad aumentada). 
Incluye el porcentaje estimado de preferencia para cada categoría y 
destaca en color la categoría con mayor crecimiento esperado.
```
    ![Captura de pantalla mostrando Analyst seleccionado en el menú de M365 Copilot.](../Prompts/Media/researcher.png)  


1. Click **Submit**.  

Analyst hará lo siguiente:  

- Analizará el conjunto de datos.  
- Identificará los segmentos de clientes de mayor valor.  
- Proporcionará visualizaciones que respalden las recomendaciones.

### Preguntas de Seguimiento para el Analyst Agent

Después de recibir el primer análisis, puedes hacer estas dos preguntas para profundizar en el escenario:

**Pregunta 1:**  

```text
Realiza un análisis de correlación entre el tipo de juguete ofrecido en la Cajita Feliz 
y el incremento en visitas al restaurante (medido en %). 
Identifica qué categorías tienen mayor correlación positiva con el tráfico de clientes 
y sugiere cuáles priorizar en la próxima campaña.
```

**Pregunta 2:**  

```text
Propón una estrategia de comunicación digital que complemente la campaña,  
incluyendo ejemplos de publicaciones en TikTok, dinámicas en Instagram y activaciones en restaurantes.
```


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

