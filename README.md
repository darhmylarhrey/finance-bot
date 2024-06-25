Here is the README.md file format for setting up the Streamlit chatbot application using Ollama:

```markdown
# Finance Help Chatbot

This repository contains a Streamlit application that serves as a finance help chatbot. The chatbot is powered by the Ollama API, using a model fine-tuned for answering questions related to Canadian finance.

## Features

- Custom chat interface with chat bubbles for user and bot messages.
- Sidebar displaying the user's first question.
- Real-time response to user queries.
- Automatic scrolling to the latest message.
- Clear input field after submission.

## Setup Instructions

### Prerequisites

- Python 3.7 or higher
- Pip (Python package installer)

### Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/darhmylarhrey/finance-help-chatbot.git
    cd finance-help-chatbot
    ```

2. **Create a virtual environment:**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. **Install the required packages:**
    ```bash
    pip install -r requirements.txt
    ```

4. **Install Ollama CLI:**
    ```bash
    pip install ollama-cli
    ```

### Running the Application

1. **Start the Streamlit app:**
    ```bash
    streamlit run app.py
    ```

2. **Open the app in your browser:**
    The app will automatically open in your default web browser. If not, navigate to `http://localhost:8501` to view the application.

## Application Structure

- `chat-bot.py`: Main application file that contains the Streamlit code for the chatbot.
- `requirements.txt`: List of Python packages required to run the application.

## Main Components

- **Custom Page Style**: The CSS for styling the chat interface and sidebar.
- **Model Creation**: Script to create the `finance_chat_bot` model using Ollama.
- **Chat History**: Container to display the conversation history between the user and the bot.
- **Input Handling**: Form for user to input questions and receive responses from the bot.

## Example Usage

1. **First Question**: The first question should be entered in the input field provided on the sidebar when you start the app. This will be processed and displayed both in the chat history and as static text in the sidebar.
2. **Further Questions**: After the initial question, use the input field at the bottom of the chat history to ask more questions. Click the "Send" button to submit.

## Screenshots

### Initial Screen
![Initial Screen](screenshots/initial_screen.png)

### Chat Interface
![Chat Interface](screenshots/chat_interface.png)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any changes.

## Contact

For questions or suggestions, feel free to reach out to [abobarinabdulafeez@gmail.com](abobarinabdulafeez@gmail.com).

---

Feel free to customize this README file to fit your specific project needs and provide more detailed instructions or explanations where necessary.
```
