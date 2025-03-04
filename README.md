# Markdown to Google Docs Converter

## Description
This is a Google Docs script that converts a Markdown file into a Google Docs document in your Google account.

## Setup Instructions
* Upload the `.ipynb` file to Google Colab.
* Upload a Markdown file to your Colab working directory.
* Set the global variable `MARKDOWN_FILE_NAME` to match your Markdown file's name.

## Dependencies
This script must be executed in the Google Colab environment. If running elsewhere, update the `GoogleDocsAPIHandler.__authenticate` function accordingly.

## Running in Colab
* Click "Runtime" → "Run All".
* A login prompt will appear; authenticate the application to grant permission to create Google Docs in your account.
* If successful, the script will output a link to the converted Google Docs document.
