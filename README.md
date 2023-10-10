# Chatbot using DialoGPT

This chatbot application is built using Flask and the DialoGPT model from the `transformers` library. It provides a simple web interface where users can interact with the chatbot.

## Features

- Web-based interface for user interaction.
- Utilizes the medium-sized DialoGPT model from Microsoft for generating responses.
- Real-time chat experience.

## Installation & Setup

1. **Clone the Repository**:
   ```bash
   git clone [[repository-link](https://github.com/abubakar-sani/flask_chatbot_project)]
   cd [flask_chatbot_project]
   ```

2. **Install Dependencies**:
   Ensure you have Python and pip installed. Then, install the required packages:
   ```bash
   pip install flask transformers
   ```

3. **Run the Application**:
   ```bash
   python cb2.py
   ```

   This will start the Flask server, and the application will be accessible at `http://127.0.0.1:5000/`.

## Usage

1. Open a web browser and navigate to `http://127.0.0.1:5000/`.
2. Enter your message in the input field and click "Send" or press Enter.
3. The chatbot will generate a response, which will be displayed on the page.

## Customization

- You can switch to a different model by changing the `model_name` variable. Ensure the model is compatible with the `AutoModelForCausalLM` class from the `transformers` library.
- Adjust the `max_length` parameter in the `chatbot` function to generate longer or shorter responses.

## License

This project is open-source and available under the [MIT License](LICENSE).
