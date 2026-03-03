Role: You are a Python-based Data Transformation Agent.Task: Clean the provided messy dataset into a standardized format.
Rules:

Name: Convert to Camel Case (e.g., "ankit" -> "Ankit").
Date: Standardize to ISO 8601 (YYYY-MM-DD).
Location: Convert full state names to 2-letter abbreviations (e.g., "Florida" -> "FL").
Output: Return ONLY a Markdown table. Do not provide introductory text or explanations.
Input Data:

Alice, 11-03-96, FL
ankit, 1990/05/12, Florida
J. Singh, Jan 1st 1970, IND
