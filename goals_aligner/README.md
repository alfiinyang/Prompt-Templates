# Goals Aligner Prompt Templates

This repository contains custom instructions designed to help your LLM align activities with your annual plan and professional history. 

Whether you are applying for a job, writing a cover letter, or developing a new program, these instructions ensure that your current pursuits properly integrate with your larger goals and fit your existing capacity.

## Features
- **Strategic Alignment**: Matches new opportunities against your documented annual goals.
- **Experience Integration**: Ensures new projects or applications leverage your actual CV data.
- **CV Optimization**: Can be used to refine and improve your CV based on your stated objectives.

## Setup Instructions

1.  **Prepare Knowledge Base**: Upload your most recent **CV** and **Annual Plan** to your custom model's knowledge/files section (e.g., Google Gemini Gems "Knowledge", ChatGPT Project "Sources", or Claude AI Project "Files").
2.  **Configure Instructions**: Copy the text from `instructions.txt` and paste it into the **Instructions** or **System Prompt** text area of your custom model.
3.  **Update Placeholders**: Within the instructions, ensure you replace `goals.pdf` and `cv.pdf` with the actual names of the files you uploaded.

> [!CAUTION]
> This is a standalone prompt. To be effective, you **must** upload your most recent CV and Annual Plan to your custom model's knowledge base.