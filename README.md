# SurveyRaby

## Overview
This open-source project aims to write surveys faster.

## Getting Started
### Prerequisites
- Python 3.8+
- Dependencies listed in `requirements.txt`
- Cuda installed GPU (Windows)
- Download database from [here](https://1drv.ms/u/c/8761b6d10f143944/EaqWZ4_YMLJIjGsEB_qtoHsBoExJ8bdppyBc1uxgijfZBw?e=2EIzti)

### Installation
1. Clone the repository
2. Navigate to the project directory
3. Install the required dependencies:

```
pip install -r requirements.txt
```

### Run

python launch_survey.py --topic "Comparative Analysis: Prediction Markets vs Traditional Polling in the 2024 US Presidential Election" 
               --gpu 0
               --saving_path ./output
               --model gpt-4o-2024-05-13
               --section_num 7
               --subsection_len 700
               --rag_num 60
               --outline_reference_num 1500
               --db_path ./database
               --embedding_model nomic-ai/nomic-embed-text-v1
               --api_url https://api.openai.com/v1/chat/completions
               --api_key sk-xxxxxx 