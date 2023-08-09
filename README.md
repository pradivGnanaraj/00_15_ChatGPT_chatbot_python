# Chatbot Application with OpenAI and PyQt6

This is a simple chatbot application built using PyQt6 for the graphical user interface and the OpenAI API for generating responses. The application allows users to interact with the chatbot, sending messages and receiving responses in a conversational manner.

## Features

- Interactive GUI using PyQt6 for user input and chat display.
- OpenAI API integration for generating chatbot responses.
- User messages and bot responses are displayed with color-coded styling.

## Requirements

- Python 3.x
- PyQt6
- OpenAI Python library

## Getting Started

1. Clone the repository:

```sh
git clone https://github.com/yourusername/chatbot-app.git
cd chatbot-app
```

2. Install dependencies:

```sh
pip install pyqt6 openai
```

3. Obtain an OpenAI API key:

   - Sign up for an OpenAI account if you don't have one.
   - Create an API key from your OpenAI account settings.

4. Update the `backend.py` file:

   - Replace `"YOUR OPENAI API KEY"` with your actual OpenAI API key.

5. Run the application:

```sh
python main.py
```

## Usage

- Launch the application.
- Type a message in the input field and press `Enter` or click the "Send" button.
- The chat area will display your message and the bot's response.

## Customization

- You can modify the chatbot's behavior by adjusting parameters in the `backend.py` file, such as the `engine`, `max_tokens`, and `temperature` values.
- Customize the GUI layout and styling by modifying the `ChatbotWindow` class in the `main.py` file.

## Note

- This is a simple example to demonstrate the integration of PyQt6 and the OpenAI API for creating a chatbot. More advanced features, error handling, and security considerations are not covered in this example.

## Contributions

If you have any suggestions, improvements, or feature requests, feel free to create an issue or a pull request on the [GitHub repository](https://github.com/yourusername/chatbot-app).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```

Remember to replace `"YOUR OPENAI API KEY"` with your actual OpenAI API key in the `backend.py` file before distributing the application.