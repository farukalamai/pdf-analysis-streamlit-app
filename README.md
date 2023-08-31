
![PDF-Analyzer](https://github.com/farukalampro/pdf-analysis-streamlit-app/assets/92469073/0adc9c1a-a273-458b-9fb3-ad9b6dba2f4b)


**Try the app here:** [PDF Analysis Tool on Streamlit Cloud](https://pdf-analysis-tool.streamlit.app/)

# PDF Analysis Tool

The PDF Analysis Tool serves as a question-answering solution, enabling users to upload PDF or TXT files and inquire about the document's contents. This application employs diverse retrievals like similarity search and support vector machines to furnish pertinent responses.

## Features

- Import PDF or TXT files
- Select the retriever type: Similarity Search or Support Vector Machines
- Create example question-answer pairs from the provided documents
- Pose queries related to the document content
- Receive responses from the application using the chosen retriever approach

## Installation

Clone this repository:

```bash
git clone https://github.com/farukalampro/pdf-analysis-streamlit-app.git
cd pdf-analysis-streamlit-app
```

Create a virtual environment and install the required packages:

```bash
  python -m venv env
```
 - For Windows:
```bash
  .\env\Scripts\activate
```
 - For macOS/Linux:
```bash
  source env/bin/activate
```

## Usage
To run the app, simply execute the following command:

```bash
streamlit run pdf.py
```

After running the command, you can access the app through your web browser using the provided URL.


