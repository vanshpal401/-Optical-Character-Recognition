---
title: OCR_Project
app_file: app.py
sdk: gradio
sdk_version: 4.44.0
---
# OCR Web Application with Gradio

This project implements an Optical Character Recognition (OCR) web application using EasyOCR and Gradio, allowing users to upload images and extract text in Hindi and English. The application also highlights specific keywords in the extracted text.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Running the Application](#running-the-application)
- [Deployment](#deployment)
- [Usage](#usage)
- [License](#license)

## Prerequisites

Before you begin, ensure you have the following installed on your local machine:

- Python 3.7 or higher
- pip (Python package installer)

## Installation

1. **Clone the repository** (if applicable):
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

2. **Install the required libraries**:
   Open your command line interface (Command Prompt on Windows, Terminal on macOS/Linux) and run the following command:
   ```bash
   pip install easyocr gradio numpy
   ```

## Running the Application

1. **Create a new Python file** (if you haven’t done so):
   Create a file named `app.py` and copy your code into it.

2. **Navigate to the directory** where your `app.py` file is located:
   ```bash
   cd path/to/your/directory
   ```

3. **Run the script**:
   Execute the following command in your terminal:
   ```bash
   python app.py
   ```

4. **Access the Gradio interface**:
   After running the script, you should see output in your command line indicating that Gradio is launching. Open a web browser and navigate to the provided URL (usually `http://127.0.0.1:7860/`).

## Deployment

### Sharing with Gradio Hub

You can share your app with others using Gradio Hub. To do this:

1. Sign up for a Gradio account.
2. Follow the instructions on the [Gradio documentation](https://gradio.app/docs/#share) to upload and share your app.

### Deploying on Cloud Platforms

If you want to deploy your Gradio app on platforms like Heroku, AWS, or Google Cloud, follow these general steps:

1. **Set up a web server** using Flask or FastAPI.
2. **Create a `requirements.txt`** file that includes all dependencies:
   ```bash
   pip freeze > requirements.txt
   ```
3. **Follow platform-specific deployment instructions** to push your code to the cloud.

## Usage

1. **Upload an image**: Click on the "Upload Image" button and select an image file containing text.
2. **Enter a keyword**: Type in a keyword to search and highlight within the extracted text.
3. **View results**: The application will display the extracted text, JSON output, and highlighted text.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
