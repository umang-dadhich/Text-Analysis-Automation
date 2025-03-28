# Text-Analysis-Automation
The objective of this assignment is to extract textual data articles from the given URL and perform text analysis to compute variables that are explained below.

## 🚀 Overview
This project automates web article text extraction and analysis. It uses web scraping and Natural Language Processing (NLP) to compute sentiment scores, readability indices, and linguistic metrics.

## 🎯 Objective
- **Extract textual content** from provided URLs.
- **Process and clean** the extracted text.
- **Perform text analysis** using NLP techniques.
- **Store results** in a structured output format.

## 🔥 Features
✅ **Web Scraping** - Extracts text using BeautifulSoup/Selenium/Scrapy.  
✅ **Text Cleaning** - Removes unnecessary elements like headers & footers.  
✅ **NLP Analysis** - Computes sentiment, readability, and complexity scores.  
✅ **Structured Output** - Saves results in Excel/CSV format.

## 🛠️ Technologies Used
- **Python**
- **BeautifulSoup / Selenium / Scrapy** (for web scraping)
- **NLTK / TextBlob** (for text processing & sentiment analysis)
- **Pandas** (for data handling and exporting)
- **OpenPyXL** (for Excel file operations)

## 📂 Data Extraction
- URLs are listed in `Input.xlsx`.  
- The script extracts **only** the article title & main content.  
- Extracted text is saved as `.txt` files (named using `URL_ID`).  

## 📊 Text Analysis
The extracted text is analyzed based on the following metrics:

| Metric | Description |
|--------|------------|
| **POSITIVE SCORE** | Measures positive sentiment |
| **NEGATIVE SCORE** | Measures negative sentiment |
| **POLARITY SCORE** | Determines overall sentiment |
| **SUBJECTIVITY SCORE** | Measures how opinionated the content is |
| **AVG SENTENCE LENGTH** | Average words per sentence |
| **PERCENTAGE OF COMPLEX WORDS** | Measures text complexity |
| **FOG INDEX** | Readability score |
| **AVG NUMBER OF WORDS PER SENTENCE** | Readability measure |
| **COMPLEX WORD COUNT** | Counts difficult words |
| **WORD COUNT** | Total number of words |
| **SYLLABLES PER WORD** | Measures word complexity |
| **PERSONAL PRONOUNS** | Counts first-person pronouns |
| **AVG WORD LENGTH** | Measures lexical complexity |

## 📤 Output Format
- The processed data is saved as **`Output.xlsx`**, following the format in `Output Data Structure.xlsx`.  
- It includes all input variables and computed analysis metrics.

## 🛠️ Installation & Usage

### 🔗 Prerequisites
Ensure Python is installed and install required libraries:
```bash
pip install pandas numpy beautifulsoup4 selenium nltk textblob openpyxl

