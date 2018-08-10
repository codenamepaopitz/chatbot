# Chatbot
Medicare Chatbot

### Requirements
    Python = 2.x.x
    Flask
    Aiml
    pip

## Installation

1. Clone and navigate to chatbot directory.

2. Install the required packages.
    ```bash
    pip install -r requirements.txt
    ```

3. Run the python server.
    ```bash
    python main.py
    ```
4. Open **http://127.0.0.1:5000** in your browser.

## Querying Response Using Postman

1. Install Postman
2. Change HTTP method to POST
3. Url is: http://localhost:5000/ask
4. On the Body Section choose form-urlencoded
5. Key: messageText
   Value: Anythin you want to ask.