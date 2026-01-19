Smart Cold Email Generator

A smart cold email generation tool designed for service-based companies, built using Groq, LangChain, and Streamlit. The application enables users to enter the URL of an organization’s job or careers page. It automatically scans the page, identifies open job roles, and generates customized cold outreach emails tailored to those roles.The generated emails also include relevant portfolio or project links, retrieved from a vector database, ensuring alignment with the job requirements and increasing response effectiveness.
Example Use Case

Consider the following scenario:

Amazon is looking to hire a Senior Backend Developer and is investing significant effort in recruitment, onboarding, and training.

TechNova, a software solutions firm, can offer an experienced developer on a contractual or dedicated basis.

A business development executive from TechNova (Ananya) decides to approach Amazon through a personalized cold email, highlighting relevant expertise and portfolio projects.

This tool automates the creation of such targeted emails efficiently.

Setup Instructions

Generate an API key from Groq:
https://console.groq.com/keys

Navigate to the app/ directory and update the .env file:

GROQ_API_KEY=your_api_key_here


Install required dependencies:

pip install -r requirements.txt


Launch the application:

streamlit run app/main.py
