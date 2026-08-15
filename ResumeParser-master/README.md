# AI Resume Parser

## Internship Project

This project is developed as part of my Artificial Intelligence Internship at Codtech IT Solutions Private Limited.

**Intern Name:** Sanaya  
**Intern ID:** `CITS6709`  
**Domain:** Artificial Intelligence  
**Duration:** 6 Weeks  
**Internship Period:** 08 July 2026 - 19 August 2026  
**Organization:** Codtech IT Solutions Private Limited  

## Project Overview

The AI Resume Parser is an automated resume processing system designed to extract relevant information from resumes and convert unstructured resume data into structured information.

The system processes resume documents, extracts important candidate details, identifies relevant skills and educational information, and generates structured output for resume screening and analysis.

## Features

- Automated resume parsing
- Candidate information extraction
- Education and university identification
- Skill extraction
- Structured CSV output
- Batch processing of resumes
- Configurable parsing and extraction settings
- NLP-based information extraction

## Technologies Used

- Python
- spaCy
- PyPDF
- Pandas
- YAML
- Natural Language Processing (NLP)

## Project Structure

```text
AI-Resume-Parser/
│
├── bin/
│   ├── main.py
│   ├── field_extraction.py
│   ├── pdf2text.py
│   └── lib.py
│
├── confs/
│   └── config.yaml.template
│
├── data/
│   ├── input/
│   │   └── example_resumes/
│   ├── output/
│   └── schema/
│
├── requirements.txt
└── README.md
```

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/AI-Resume-Parser.git
cd AI-Resume-Parser
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Install spaCy Model

```bash
python -m spacy download en_core_web_sm
```

## Usage

Place the resumes you want to process inside:

```text
data/input/
```

Navigate to the `bin` directory:

```bash
cd bin
```

Run the parser:

```bash
python main.py
```

The processed results will be generated in the configured output directory.

## Input

The system accepts resume documents as input.

Example:

```text
data/
└── input/
    ├── resume1.pdf
    ├── resume2.pdf
    └── resume3.pdf
```

## Output

The extracted resume information is converted into structured data for further analysis and candidate screening.

Example:

```text
data/
└── output/
    └── resumes.csv
```

## Configuration

The parser can be configured using the YAML configuration template:

```text
confs/config.yaml.template
```

The configuration can be used to customize:

- Input directory
- Output directory
- Skills to be extracted
- Universities to identify
- Resume fields
- Output schema

## Applications

The Resume Parser can be used for:

- Automated resume screening
- Candidate information extraction
- Recruitment workflows
- Resume analysis
- Skill-based candidate filtering
- Creating structured candidate datasets

## Future Enhancements

- Web-based user interface
- Support for DOCX and additional resume formats
- Improved NLP-based entity extraction
- Semantic resume search
- Large Language Model (LLM) integration
- AI-powered resume summarization
- Candidate ranking based on job requirements
- Improved extraction accuracy

## Internship Information

| Details | Information |
| --- | --- |
| Intern Name | Sanaya |
| Intern ID | `CITS6709` |
| Domain | Artificial Intelligence |
| Organization | Codtech IT Solutions Private Limited |
| Duration | 6 Weeks |
| Internship Period | 08 July 2026 - 19 August 2026 |

## Acknowledgement

This project was developed as part of the Artificial Intelligence Internship at Codtech IT Solutions Private Limited.

## License

This project is developed for educational and internship purposes.
