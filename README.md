# Flask-OpenAI-Djangbot
A Flask chatbot app(Djangbot) powered by OpenAI's GPT. Djangbot allows users to interact with different characters, each with their unique backgrounds and personalities. Additionally, it features a user-friendly and mobile responsive chatbot UI.

<img src="https://github.com/iamdjangod/flask_openai_djangbot/blob/main/djangbot_1.png">


![Alt text](https://github.com/iamdjangod/flask_openai_djangbot/blob/main/djangbot_2.png)


![Python Version](https://img.shields.io/badge/Python-3.7%20%7C%203.8%20%7C%203.9-blue)
![Flask Version](https://img.shields.io/badge/Flask-2.0.1-green)
![OpenAI GPT Version](https://img.shields.io/badge/OpenAI%20GPT-3.5%20Turbo-yellow)


## Features

- Utilize OpenAI's GPT for intelligent responses.
- User-friendly chatbot interface built with HTML and Flask.
- Store chat history for each character in separate text files.
- Easy-to-define character profiles.

## Getting Started

### Prerequisites

- Python 3.7+ installed on your system.
- Flask 2.0.1 and OpenAI Python SDK installed.
- Set up your OpenAI API key.

### Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/iamdjangod/Flask-OpenAI-Djangbot.git
    ```

2. 2. Navigate to the project directory:https://github.com/iamdjangod/Flask-OpenAI-Djangbot
```bash
cd flask-openai-djangbot
```
3. Install the required Python packages:
```bash
pip install -r requirements.txt
```
This command will install all the necessary Python packages and dependencies required for Djangbot app.


4. Configure your OpenAI API key:
In order to use OpenAI's GPT for intelligent responses in your chatbot, you'll need to configure your OpenAI API key in the app.py file. Follow these steps:

a. Open app.py in a text editor or code editor of your choice.
```bash
gedit app.py  # or use your preferred code editor
```
b. Locate the following line in app.py:
```python
openai.api_key = "your-api-key"
```
c. Replace "your-api-key" with your actual OpenAI API key. It should look something like this:
```python
openai.api_key = "open_ai_secret_key"
```
d. Configure your bot
```python
# Define the role of the bot
role = ‘home service’

# Define the impersonated role with instructions
impersonated_role = f"""
    You are going to act as {name}. Your role is {role}.
"""
```
e. Save the changes to the app.py file and exit the text editor.
With these steps completed, Djangbot app is now set up and ready to be launched.

5. Usage
Now that you've completed the setup, you can use Djangbot App:


a. Start the Flask app:
```bash
python app.py
```
b. Open your web browser and go to http://localhost:5000 to interact with Djangbot.

Djangbot app is now fully configured and ready for use. You can customize character profiles and the chatbot UI as needed to create engaging and interactive conversations.

