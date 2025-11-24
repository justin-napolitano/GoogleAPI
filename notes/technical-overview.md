---
slug: github-googleapi-note-technical-overview
id: github-googleapi-note-technical-overview
title: GoogleAPI
repo: justin-napolitano/GoogleAPI
githubUrl: https://github.com/justin-napolitano/GoogleAPI
generatedAt: '2025-11-24T18:37:49.269Z'
source: github-auto
summary: >-
  GoogleAPI is a Python library that simplifies interactions with Google Sheets
  and Google Drive. It lets you access and manipulate Google Sheets data and
  Drive files with ease, especially when using pandas.
tags: []
seoPrimaryKeyword: ''
seoSecondaryKeywords: []
seoOptimized: false
topicFamily: null
topicFamilyConfidence: null
kind: note
entryLayout: note
showInProjects: false
showInNotes: true
showInWriting: false
showInLogs: false
---

GoogleAPI is a Python library that simplifies interactions with Google Sheets and Google Drive. It lets you access and manipulate Google Sheets data and Drive files with ease, especially when using pandas. 

## Key Features
- Integrate with Google Sheets via the Sheets API
- Access metadata and create folders on Google Drive
- Pythonic wrapper for Google APIs
- Upcoming feature: export pandas DataFrames to Google Sheets

## Quick Start

### Prerequisites
- Python 3.x
- Enabled Sheets and Drive APIs in a Google Cloud project
- OAuth 2.0 credentials in `credentials.json`

### Installation

```bash
pip install --upgrade google-api-python-client google-auth google-auth-oauthlib
```

### Usage 

1. Place `credentials.json` in the project directory.
2. Import and initialize:

```python
from GoogleServices import GoogleAPI

google_api = GoogleAPI()
```

3. Use `google_api.SheetsApp` and `google_api.DriveApp` for operations.

## Gotchas
Don’t forget to set up your Google Cloud project correctly. Misconfigurations can lead to authentication issues.
