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
