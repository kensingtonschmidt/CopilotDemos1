---
demo:
    title: 'HR Demo'
---

[Back to Index](https://microsoftlearning.github.io/Copilot-Immersion-Experience/)

# HR Demo

**Scenario:**  
Use Copilot to streamline the hiring process for a Senior Animation Designer by generating a job description, comparing candidate resumes, and drafting an email to coordinate next steps with the hiring team.

## Demo Setup

The sample documents can be found in the MS-40XX GitHub repository [here](https://github.com/MicrosoftLearning/Copilot-Immersion-Experience/tree/master/ResourceFiles):

The specific files needed for this demo are:

- [Design_Team_Responsibilities.docx](https://github.com/MicrosoftLearning/Copilot-Immersion-Experience/raw/master/ResourceFiles/Graphic_Design_Institute_Design_Team_Responsibilities.docx)

- [Resume_Patti_Fernandez.docx](https://github.com/MicrosoftLearning/Copilot-Immersion-Experience/raw/master/ResourceFiles/Resume_Patti_Fernandez.docx)

- [Resume_Nestor_Wilke.docx](https://github.com/MicrosoftLearning/Copilot-Immersion-Experience/raw/master/ResourceFiles/Resume_Nestor_Wilke.docx)

- [Resume_Holly_Dickson.docx](https://github.com/MicrosoftLearning/Copilot-Immersion-Experience/raw/master/ResourceFiles/Resume_Holly_Dickson.docx)

- [Resume_Alex_Wilber.docx](https://github.com/MicrosoftLearning/Copilot-Immersion-Experience/raw/master/ResourceFiles/Resume_Alex_Wilber.docx)

**NOTE:** It can take up to 10 minutes for these files to sync to your OneDrive once downloaded. It is advised that you download these files to your OneDrive account prior to delivering this demo. If the files are not available in your OneDrive, you can open the documents and copy the shared file links to use in the demo.

## Demo Steps

### **Step 1** (Copilot in Word)

Let’s start by asking Copilot in Word to generate a job description.

1. Open Word (either in your browser or desktop application).

1. In the **"Describe what you'd like to write"** prompt box, type the following:

    ```text
    I'm the HR Manager at the Graphic Design Institute. We've currently started the hiring process for a new Senior Animation Designer. Please review the attached document that outlines the job responsibilities for this role and create a job description based on those responsibilities.
    
    [copy link or reference file to Design_Team_Responsibilities.docx]
    ```

1. Select **Keep it** or, if you have time, demonstrate editing the document using Word. Once finalized, save the document as **GDI_Job_Description.docx** and copy the shared URL to be used in the next step. (Enable autosave and select your OneDrive account if prompted.)

    ![Share link.](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

### **Step 2** (Copilot Chat)

Next, we will use Copilot Chat to compare resumes we've received to the job description and identify the best candidates.

1. Open a browser and navigate to [M365copilot.com](https://m365copilot.com/).

1. In the prompt window, type the following:

    ```text
    We are hiring for the position of Senior Animation Designer. Please analyze the attached resumes and compare them to the requirements outlined in the job description provided here: [paste link to GDI_Job_Description.docx]. Rank the candidates from most qualified to least qualified, based on their alignment with the role.

    [copy shared links, reference file using slash "/", or upload files for:
    Resume - Patti Fernandez
    Resume - Nestor Wilke
    Resume - Holly Dickson
    Resume - Alex Wilber]
    ```

1. Optionally, you can ask Copilot Chat to export its response to a Word document to highlight this feature.

### **Step 3** (Copilot in Outlook)

Lastly, use Copilot in Outlook to draft an email to the hiring team regarding the top candidates.

1. Open Outlook (either in your browser or desktop application).

1. Select **New Email**.

1. Select **Copilot** in the ribbon. From the drop-down menu, choose **Draft with Copilot**.

1. In the **"What do you want this email to say?"** prompt window, type the following:

    ```text
    Please draft an email to the hiring team to share that Nester Wilke and Patti Fernandez align best with the Senior Animation Designer role based on their qualifications. Ask if we should move forward with scheduling interviews for these candidates.
    ```

[Back to Index](https://microsoftlearning.github.io/Copilot-Immersion-Experience/)