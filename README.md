# MediSelect: AI-Based Hospital Recommendation Engine
In the medical field, it is important to make informed decisions both for the patient and medical practitioner. Deciding on the proper hospital or organization for appointments is usually cumbersome, given a large number of available options. To aid this decision-making, we can utilize sophisticated AI algorithms that compare corresponding data from organizations and hospitals.

This project seeks to develop an AI system that analyzes hospital or organization records and offers customized recommendations based on in-depth data analysis. Through the integration of Retrieval-Augmented Generation (RAG) and LangChain-based AI agents, the system retrieves useful insights from a hospital dataset (in CSV format) and utilizes a generative model to offer a recommendation to the user.

The system is intended to:
Upload and process hospital data – The data, including satisfaction scores and performance indicators, is uploaded into the system.
Query handling – The user provides a query concerning hospital choice, e.g., asking information about the performance of a given hospital.
Data retrieval – Employing RAG, the system retrieves appropriate data from the hospital dataset to respond to the query.
Analysis and suggestion – The agent based on LangChain analyzes the data retrieved and makes a suggestion regarding whether the user should make an appointment with the hospital or not.
This system can be useful for medical patients and institutions interested in offering tailored, data-backed recommendations to their users. Automating data processing and decision-making, the system presents a seamless, efficient means of assessing hospitals and institutions for health appointment considerations.

# Technologies used:
Google Gemini AI: Powers generative responses to user queries and processes natural language.
RAG (Retrieval-Augmented Generation): Combines data retrieval with AI generation to provide accurate, context-aware answers.
CSV File Handling: Stores and processes hospital data for query responses.
LangChain : Runs the AI agent to process user queries and generate responses based on data.
Few Shot Prompting Technique : The model is given a few examples of input-output pairs in the prompt itself to guide its responses.
Dataset Used
Link : https://www.kaggle.com/datasets/blueblushed/hospital-dataset-for-practice

This dataset contains records of 1000 patients treated at a hospital, including demographic information, medical conditions, treatments administered, medical expenses incurred, and current health status. Explore various patterns, trends, and insights in patient care, recovery rates, and treatment efficacy using this rich dataset.
