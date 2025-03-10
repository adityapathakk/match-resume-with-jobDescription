# Match Resumes With Job Description

Have a ton of resumes that you just can't check manually? Want to filter the top resumes automatically?<br>
Well then look no further, and use this simple Python script to automate the filtering of resumes!

- Simply assign your desired job description to the `j_d` variable `in app.py`.
- Also, migrate all the resumes that need to undergo the filtering process (for now, in PDF format) to the `resumes` directory.

## Technologies Used:
- Developed using VS Code on Windows
- Cosine & Jaccard similarity metrics, for semantic similarity and keyword similarity, respectively
- Python and its libraries - <a href = "https://huggingface.co/sentence-transformers">sentence-transformers</a>, PyMuPDF, scikit-learn, nltk, regex, and more!

###### Here's an example of the project's working.
<img src = "https://github.com/adityapathak-cubastion/match-resume-with-jobDescription/blob/main/resumeMatching_example.png">

## Future Scope
- Developing a frontend interface and connecting a backend database to store resume data
- Adding Named Entity Recognition (NER) to detect 'required skills' in the job description and improving keyword matching by specifically looking for those skills in resumes
- Using an LLM to compare the top filtered resumes with the job description to get a detailed understanding of the candidate's strengths and weaknesses
- Open ended: suggestions are welcome!
