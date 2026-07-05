# SmartPPT

SmartPPT is an AI-powered application that automatically creates PowerPoint presentations from web content. Users can either provide a list of URLs or search for a topic, and the application collects relevant information, summarizes it using Google Gemini, and generates a presentation in a predefined PowerPoint template.

## Features

- Generate presentations from URLs or search queries
- Extracts content from web pages using BeautifulSoup
- Summarizes information with Google Gemini
- Automatically creates PowerPoint slides
- Adds relevant images from web pages
- Uses a predefined presentation template for consistent formatting

## Tech Stack

- Python
- Streamlit
- LangChain
- Google Gemini 2.5 Flash
- BeautifulSoup4
- Requests
- python-pptx
- Google Search API

## Project Structure

```
SmartPPT/
├── Ai_ppt.py
├── Bracket design.pptx
├── PPT.pptx
├── requirements.txt
├── README.md
├── .gitignore
└── .streamlit/
    └── secrets.toml
```

## How It Works

1. Enter a topic or provide one or more URLs.
2. The application collects relevant web content.
3. Google Gemini summarizes the extracted information.
4. Relevant images are selected from the web pages.
5. The content and images are added to a PowerPoint template.
6. A presentation is generated and ready to download.

## Future Improvements

- Support multiple presentation themes
- Improve image selection using AI
- Export presentations in PDF format
- Add editable slide templates
- Support additional presentation layouts
