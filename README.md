# AI Research Assistant Agent

ITAI 2376 – Capstone Project  

## Overview
This agent helps users gather, summarize, and organize academic research content using external tools and reinforcement feedback.

## Features
- Topic-based search
- Source evaluation
- Citation formatting
- Structured report generation

## Tools Used
- **arXiv API** – for retrieving real academic abstracts without requiring an API key
- **Hugging Face Transformers** – used DistilBART (`sshleifer/distilbart-cnn-12-6`) for text summarization
- **Python Standard Libraries** – including `requests` for API access and `xml.etree.ElementTree` for XML parsing


## How to Run
To run the project, first clone the repository using git clone https://github.com/GregLivin/AI_Agent_Project_GregoryLivingston.git, then navigate to the project folder with cd AI_Agent_Project_GregoryLivingston. Next, install the required dependencies using pip install -r requirements.txt. Open Google Colab, go to File > Open notebook, click on the GitHub tab, and paste the repository URL: https://github.com/GregLivin/AI_Agent_Project_GregoryLivingston. From there, select and open the file FN_Code_GregL_AgentPioneers_ITAI2376.ipynb. Finally, click Runtime > Run all and follow the instructions inside the notebook. No API key is needed.





