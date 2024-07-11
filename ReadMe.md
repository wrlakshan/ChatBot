# Simple Chatbot using Python and OpenAI

This project demonstrates how to create a simple chatbot using Python and the OpenAI API. The chatbot interacts with users in a conversational manner, leveraging the gpt-3.5-turbo model.

## Prerequisites

- Python 3.x installed on your machine
- OpenAI API key

## Installation

1. **Set up a virtual environment**:
    ```sh
    pip install virtualenv
    virtualenv env
    ```

2. **Activate the virtual environment**:
    - On Windows:
        ```sh
        .\env\Scripts\activate
        ```
    - On macOS and Linux:
        ```sh
        source env/bin/activate
        ```
    - On GitBash:
        ```sh
        cd env/Scripts/
        . activate
        ```

3. **Install the required packages**:
    ```sh
    pip install -r requirements.txt
    ```

4. **(Optional) Save the installed packages**:
    ```sh
    pip freeze > requirements.txt
    ```

## Usage

1. **Create a `.env` file** in the project root directory and add your OpenAI API key:
    ```plaintext
    OPENAI_API_KEY=your_openai_api_key_here
    ```

2. **Run the chatbot script**:
    ```sh
    python app.py
    ```

## Example

When you run the script, you should be able to interact with the chatbot in your terminal:

```plaintext
You: Hello, chatbot!
Chatbot: Hello! How can I assist you today?