# InterviewPrepGPT: A tool to help people prepare their interview based on GPT-3.5 model

# Overview
This project aims to provide a professional guidance tool for job seekers using the GPT-3.5-turbo model. 

The tool offers the following functions:
- for a specific job interview: comprehensive advice on the characteristics of this job and the company.
- for a specific job position: comprehensive advice of the behavior and technical skills required.  
- an analysis of resumes to identify strengths and weaknesses based on the user's job search requirements. 

The approach includes iterative questioning and offers in-depth information to help users understand each required knowledge point thoroughly.

The project leverages the power of the GPT-3.5 model and its advanced natural language processing capabilities to deliver personalized interview preparation advice that meets the user's specific needs. The tool's core functionality involves testing various prompt statements to determine the most effective prompt that will return the desired outcome. The user interface is built using Streamlit to enhance user convenience.

Overall, this tool serves as a useful resource to assist job seekers in preparing for interviews, improving their chances of success in securing desired job opportunities.

# Website
[Huggingface Spaces](https://huggingface.co/spaces/hydai/InterviewPrepGPT)


# Critical Analysis

## What is the impact of this project? 
The impact of this project is potentially significant for job seekers. It offers personalized guidance based on their specific job search requirements and provides a comprehensive review of the knowledge and skills required for specific job positions and interviews. This tool can potentially increase the chances of job seekers succeeding in interviews and securing desired job opportunities.

Moreover, this project highlights the capabilities of advanced natural language processing models like GPT-3.5. It demonstrates how such models can be used to develop personalized tools and resources that meet specific user needs, providing a level of customization and personalization that was not previously possible.

## What does it reveal or suggest? 
This project suggests the potential for more sophisticated and tailored applications of natural language processing in various domains beyond job search and interviews. It is a promising direction for future research and development of more sophisticated and personalized natural language processing tools that can be applied in various settings.

## Next Step
- Enhance UI design
- Further improve existing functionalities:
  - Enhance "Analyze Resume" feature:
      - Provide support for docx file format.
      - Utilize a powerful Deep Averaging Network Encoder to generate embeddings and break the resume into smaller chunks to better understand different sections of the uploaded resume.
  - Optimize prompt selection.
- Introduce new functionality: Mock Interview
  - Evaluate and offer suggestions for each user response.
  - Provide voice support.


# Resource links

1. [chatgpt](https://chat.openai.com/)
2. [openai-api](https://platform.openai.com/docs/api-reference/introduction)
3. [awesome-prompt](https://github.com/f/awesome-chatgpt-prompts)
4. [openai-cookbook](https://github.com/openai/openai-cookbook)
5. [How to Use ChatGPT to Prepare for an Interview](https://www.griproom.com/fun/how-to-use-chatgpt-to-prepare-for-an-interview)


# Code demonstration
[Links to code](app.py)

# Links to video
[Overview video](https://drive.google.com/file/d/1Z_0-nYyAei59TAUIo3FXfH6U8Iz1kObL/view?usp=sharing)