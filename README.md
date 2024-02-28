# Legal-Document-Automation-and-Customization-Tool
A tool for generating and customizing legal documents, streamlining workflows for legal professionals.
The Legal Document Automation and Customization Tool is a project designed to simplify the process of generating legal documents through automation and customization. It utilizes Natural Language Processing (NLP) techniques to match user input with pre-existing legal documents in the dataset. The tool currently provides a basic version of the use case, supporting three types of documents: purchase agreements, will templates, and divorce documents.

## Features
+ **Search Functionality:** Users can search for specific legal documents using a search bar.  

+ **NLP Techniques:** Utilizes NLP techniques such as text preprocessing (lowercasing, tokenization, stop words removal) to analyze user input.

+ **Cosine Similarity Matching:** Matches user input with documents in the dataset using cosine similarity.

+ **Streamlit UI:** Implements a basic UI using Streamlit for user interaction.

+ **Document Customization:** Users have the option to edit the generated document and regenerate it according to their requirements.

## Working and Results

**Step 1:** Upon opening the app, it displays the following web page.
![snip1](https://github.com/nikithaundavalli/Legal-Document-Automation-and-Customization-Tool/assets/128024373/858eef94-07a8-452e-9878-a68e9db027f6)
**Step 2:** User can input the query in left side search bar to search for the documents and the related document will be displayed on the right side.
![snip2](https://github.com/nikithaundavalli/Legal-Document-Automation-and-Customization-Tool/assets/128024373/833aecec-64e0-4db3-9db8-fa1651a58cc7)
**Step 3:** The user has the option to edit the document(if needed) according to their choice. The edit option is displayed just below the document template.
![snip3](https://github.com/nikithaundavalli/Legal-Document-Automation-and-Customization-Tool/assets/128024373/8944f6cd-fc1f-4817-b71f-f4cf24fa5f08)
**Step 4:** After editing the document, the user has the option to generate a new document with the edited details.
![snip4](https://github.com/nikithaundavalli/Legal-Document-Automation-and-Customization-Tool/assets/128024373/ef231707-7e01-42ab-95ea-904a18e45572)

## Future Works
Due to the time constraints, the work is restricted to the basic functionalities. In future it can be extended to
+ Train a ML model with huge dataset to increase the accuracy in selection of related documents.
+ Allow the user to download the generated document.
+ Provide the searching option using voice command.
+ Training the dataset by user feedback.
