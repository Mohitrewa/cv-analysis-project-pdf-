how to run this project use google colabs -https://drive.google.com/file/d/15scVTU4yz_Qdf_e2_I_M3hdQnbCA6Yj7/view?usp=drive_link
ou are installing the following libraries:

gtts (Google Text-to-Speech)
PyPDF2 (PDF processing)
nltk (Natural Language Toolkit for text processing)
PDF Processing
You have functions to:

Extract Sections from PDF: extract__section reads the PDF and extracts text.
Extract Experience Section: get_exp_sction identifies the experience section in the text.
Extract and Format Dates: extract_total_experience and format_dates extract date ranges and format them into a list of date pairs.
Calculate Total Experience: calculate_total_years calculates the total years and months of experience based on the date ranges.
Get Experience from PDF: get_exp_year_from_pdf combines the above functions to get the total experience from a PDF.
Skills Section
You have functions to:

Extract Skills Section: get_skill_section identifies the skills section in the text.
Create Skill Dictionary: create_skill_dict creates a dictionary of skills from the skills section.
Find Skill Usage: find_skill_usage counts the occurrence of each skill in the extracted text.
Chatbot Interaction
You are developing a chatbot function:

Get Professional Vocabulary: get_professional_words, get_professional_vocab_exp, and get_professional_vocab_skill generate sets of related professional terms.
Check Required Information: check_required_info checks if the required terms are present in the experience or skills sections.
Preprocess Text: preprocess_text tokenizes and preprocesses input text.
Provide Answer: provide_answer processes the input question and returns relevant information based on the preprocessed question.
Execution
At the end, you have the execution part where:

You specify the PDF path.
Extract years of experience and print it.
Extract skills and print them.
