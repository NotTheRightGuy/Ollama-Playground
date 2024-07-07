# Ollama Playground

This is a single-page React application designed to provide a playground for interacting with your local Ollama models. With this application, you can load different models, pass system prompts, change models on the fly, clear chat, and much more. UI provided by Shadcn Blocks.

## Features

- **Interact with Local Models**: Easily interact with your locally installed Ollama models.
- **Dynamic Model Loading**: Modify `model.json` to load different models.
- **System Prompts**: Pass system prompts to the models.
- **Model Switching**: Change the active model on the fly.
- **Clear Chat**: Clear the chat history with a single click.
- **User-Friendly Interface**: Intuitive and easy-to-use interface.

## Prerequisites

Before running the application, ensure you have the following installed:

- Node.js
- npm (Node Package Manager)
- Ollama server

## Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/NotTheRightGuy/Ollama-Playground
   cd Ollama-Playground
   ```

2. **Install Dependencies**

   ```bash
   npm install
   ```

3. **Start the Ollama Server**

   Make sure your Ollama server is running. Refer to the Ollama documentation for instructions on starting the server.

## Configuration

1. **Modify `model.json`**

   Edit the `model.json` file to include your locally installed models. Here is an example format:

   ```json
   [
     {
       "model_tag": "phi3",
       "model_name": "Phi 3",
       "inference_speed": "fast",
       "model_description": "Optimized for speed and can be used for real-time applications."
     },
     {
       "model_tag": "llama3",
       "model_name": "Llama 3",
       "inference_speed": "moderate",
       "model_description": "Provide a balance between speed and accuracy."
     }
   ]
   ```

   Add as many models as you need in this format.

## Running the Application

1. **Start the React Application**

   ```bash
   npm run dev
   ```

2. Open your browser and navigate to `http://localhost:3000`. You should see the Ollama Playground interface.

## Usage

- **Loading a Model**: Select a model from the dropdown to load it.
- **Passing a System Prompt**: Enter your system prompt in the input field and click "Submit".
- **Changing Models**: Use the dropdown to switch between different models.
- **Clearing Chat**: Click the "Clear Chat" button to clear the chat history.

## Contributing

We welcome contributions! If you have any suggestions, bug fixes, or new features, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---
