# Multi-Purpose Python Toolbox

This repository contains a Python script that serves as a multi-purpose toolbox, allowing you to perform various tasks by choosing a specific option. It combines web browsing, AWS management, and more, all in one place. Additionally, the script uses text-to-speech (TTS) to provide you with instructions and options.

## Features

- Web browsing: You can open websites like Google, WhatsApp, Gmail, LinkedIn, YouTube, and more directly from the script.
- AWS Management: You can launch an AWS webpage, create EC2 instances, EC2 volumes, and even an API Gateway.
- Calculator: Launch the calculator application.
- Social Media: Access Facebook and Instagram from the script.

## Usage

1. Clone the repository to your local machine:
   ```
   git clone https://github.com/vishvratnass27/python_menu_program.git
   ```

2. Install the required Python libraries if you haven't already:
   ```
   pip install pyttsx3 boto3
   ```

3. Run the Python script `toolbox.py`:
   ```
   python toolbox.py
   ```

4. Follow the instructions and enter the number corresponding to the action you want to perform.

## Dependencies

- [`pyttsx3`](https://pypi.org/project/pyttsx3/): This library is used for text-to-speech functionality, providing voice instructions and options.
- [`boto3`](https://pypi.org/project/boto3/): If you intend to use AWS-related options, you will need to configure AWS CLI with the appropriate credentials.

## Example Usage

Here's an example of how you can use this toolbox:

1. Run the script and listen to the instructions.
2. Enter the number "1" to open AWS webpage.
3. Enter the number "2" to open Google in your default web browser.
4. Enter the number "8" to launch the calculator application.

## Note

- Make sure to configure AWS CLI with your credentials if you intend to use AWS-related options.
- For social media access (Facebook and Instagram), you should have the respective websites accessible in your region.
