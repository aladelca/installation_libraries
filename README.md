# Installation guide

Guide for installing libraries for assignment 2

## Overview

This guide explains how to set up a Python virtual environment using `.venv`, activate it, and install the required packages from `requirements.txt`. Follow the instructions below for your operating system.

## Prerequisites

- **Python 3.9+** (ensure it is installed and added to your system's PATH)
- **pip** (typically installed alongside Python)

## Creating and Activating the Virtual Environment

### For macOS / Linux

1. **Open your terminal.**
2. **Navigate to your project directory:**
   ```bash
   cd /path/to/your/project

3. **Create your virtual environment:**
    ```bash
    python -m venv .venv
4. **Activate your virtual environment:**
This may change based on your OS. Check this [documentation](https://docs.python.org/3/library/venv.html) for Windows. The following code is for Mac
    
    ```bash
    source .venv/bin/activate   

5. **Installing the requirements:**
This already includes the libraries needed for the assignment

    ```bash
    pip install -r requirements.txt

6. **Running your notebook**

Make sure that, when open your notebook, this is running in the virtual environment. It should look like this in Visual Studio Code

![](https://private-user-images.githubusercontent.com/83436724/410678915-74bdb07e-1ca8-4dec-8d28-8335926a0b08.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3Mzg4ODEwMzcsIm5iZiI6MTczODg4MDczNywicGF0aCI6Ii84MzQzNjcyNC80MTA2Nzg5MTUtNzRiZGIwN2UtMWNhOC00ZGVjLThkMjgtODMzNTkyNmEwYjA4LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNTAyMDYlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjUwMjA2VDIyMjUzN1omWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTc0YTA1YmYwNWZlOTEwODk5NWJiYjNmYzI0N2Q2MmRlMzQ1ZWI2ZTRjMDc5ZjQ1ZTNjMzZkZTI1MDdhZDc1ZmImWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.qdjXQDtW0QPTE3saXWPcogM8aua-vI_UJTB8USFFMyc)


Refer to `example_notebooks.ipynb` on this repo to see an example of the application of the libraries.