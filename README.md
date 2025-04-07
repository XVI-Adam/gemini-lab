# Jasper Photo Generator

Generates images of Brother Jasper (MU mascot) near landmarks using the Google Gemini API and provides a simple web interface with Taipy GUI.

## Key Features

* Generates location-based mascot images.
* User-friendly web interface.
* Basic image caching in Google Drive.

## Prerequisites

* Python 3.6+
* Google Gemini API Key (in `.env` file)
* Required libraries (`pip install google-generativeai python-dotenv taipy`)
* Initial image: `first_test_image.jpeg`

## Setup

1.  Install prerequisites.
2.  Create `.env` with `GEMINI_API_KEY=YOUR_KEY`.
3.  Place `first_test_image.jpeg` in the script directory.

## Run

```bash
python your_script_name.py
```

![Brother Jasper](before.png)
![Brother Jasper in Egypt](after.png)
