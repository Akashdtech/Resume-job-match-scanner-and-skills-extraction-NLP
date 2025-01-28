# Resume-job-match-scanner-and-skills-extraction-NLP
This repository provides a simple Python script to calculate the match percentage between a resume and a job description using cosine similarity and extract key skills from the job description using spaCy. It is designed to help users quickly assess how well their resume aligns with specific job requirements.

Resume-Job Description Match Percentage:

        Calculates the similarity between a resume and job description using CountVectorizer and cosine_similarity from scikit-learn.
        Outputs the match percentage as a numeric score.

Skill Extraction from Job Description:

        Extracts key skills from the job description document using spaCy's natural language processing capabilities.
        Identifies nouns and proper nouns as potential skills.

Install the required libraries using the following commands:

        pip install docx2txt
        pip install spacy

Prepare Input Documents:

        Save your resume as Curriculum Vitae.docx and the job description as Job Requirements.docx.
        Place both files in the specified path (e.g., /content/).

Run the Script:

        The script will read the documents, compute the match percentage, and extract skills from the job description.

Outputs:
        Match Percentage: The similarity score between your resume and the job description.
        Extracted Skills: A list of key skills identified from the job description.
