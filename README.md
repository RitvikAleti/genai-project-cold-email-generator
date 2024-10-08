# ✉️ Cold Email Generator
Cold email generator for a services company using llama 3.1, groq, langchain and streamlit. It allows users to input the URL of a job posting on a company's careers page. The tool then extracts the job description from that page and generates personalized cold emails. These emails include relevant portfolio links sourced from a vector database, based on the specific job description.

**Imagine a scenario:**

- Meta needs a Systems Software Engineer and is spending time and resources in the hiring process, on boarding, training etc
- ExampleCompany is a software development company that can provide a dedicated software engineer to Meta. So, the business development executive from ExampleCompany is going to reach out to Meta via a cold email.

![img.png](imgs/img.png)

## Architecture Diagram
![img.png](imgs/architecture.png)

## Set-up
1. To get started, we first need to get an API_KEY from here: https://console.groq.com/keys. Inside `app/.env` update the value of `GROQ_API_KEY` with the API_KEY you created. 


2. Install the dependencies using:
    ```commandline
     pip install -r requirements.txt
    ```
   
3. Run the streamlit app:
   ```commandline
   streamlit run app/main.py
   ```
