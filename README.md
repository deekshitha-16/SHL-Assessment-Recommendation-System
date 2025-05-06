# SHL-Assessment-Recommendation-System
The SHL Assessment Recommendation System is designed to help you find the best SHL assessments for your hiring process. Whether you're looking to evaluate specific job roles, skills, or even need an assessment based on a job description, this system uses cutting-edge AI techniques to suggest the most relevant assessments.

Try the app now:

# Core Features
Tailored Recommendations:
Get personalized assessment suggestions based on job titles, skills, or free text inputs.
Works with both structured and unstructured input, such as job descriptions or links.

Smart Matching:
The system analyzes the semantic meaning of your query using Sentence-BERT embeddings.
Assessments are ranked based on similarity to your input, ensuring relevant suggestions.

Enhanced Filtering:
Additional context filtering using Gemini 1.5 Pro ensures only the most relevant assessments based on constraints like duration, required skills, etc.

User-Friendly Interface:
Built on Streamlit, this interactive web interface makes it easy for users to input queries and get recommendations in real time.

# Technologies Used
NLP:
Sentence-BERT: Converts job descriptions and assessments into embeddings to compute similarity scores.
Cosine Similarity: Used to rank assessments based on how similar they are to the user's input.

LLM Integration:
Gemini 1.5 Pro: Automatically extracts key information from job descriptions to improve recommendation accuracy.

Frontend:
Streamlit: A lightweight, Python-based frontend framework for a smooth user experience.
