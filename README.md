# WhatCMS Website Technology Enrichment

## Project Overview
This project enriches a list of website URLs using the WhatCMS API to identify the CMS and technology stack used by each website.

## Features
- Reads 50 URLs from Excel
- Calls WhatCMS API
- Extracts CMS and technology details
- Exports enriched Excel output

## Technologies Used
- Python
- Pandas
- Requests
- WhatCMS API

## How to Run

1. Install requirements:
pip install -r requirements.txt

2. Set your API key:
set WHATCMS_API_KEY=your_api_key_here

3. Run:
python whatcms_enrichment.py

## Output
Excel file containing enriched website technology data.
