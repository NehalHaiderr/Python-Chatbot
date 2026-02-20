# Simple NLTK Chatbot

This repository contains a very basic chatbot built using Python and the NLTK library.

## Requirements

- Python 3.13 (or any recent Python 3 release)
- `nltk` package

## Setup

1. Open a terminal in the project folder:

   ```powershell
   cd "C:\Users\user\OneDrive\Desktop\Chatbot with Python"
   ```

2. Create (and activate) a virtual environment:

   ```powershell
   python -m venv .venv
   .\.venv\Scripts\Activate.ps1      # PowerShell
   # or .\.venv\Scripts\activate.bat # cmd.exe
   ```

3. Install the required package:

   ```powershell
   pip install nltk
   ```

## Running the chatbot

Execute the script with Python while the virtual environment is active:

```powershell
python ChatBot.py
```

Type messages at the prompt. Enter `bye` or `goodbye` to exit.

## Notes

- The script downloads the `punkt` tokenizer data automatically on first run.
- The chatbot uses a simple list of regex-driven patterns and static responses.

Feel free to expand the `pairs` list or modify the reflections dictionary to customize behavior.
