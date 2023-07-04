# English to German Translation App

This is a simple Streamlit app that translates English text to German using the GPT-3.5-turbo model from OpenAI.

## Installation

1. Clone the repository:

   ```shell
   git clone https://github.com/vicdotdevelop/translator_aider.git
   ```

2. Navigate to the project directory:

   ```shell
   cd translator_aider
   ```

3. Install the required dependencies using pip:

   ```shell
   pip install -r requirements.txt
   ```

4. Create a new file named `.env` in the project directory and add your OpenAI API key to it:

   ```shell
   OPENAI_API_KEY=your-api-key
   ```

   Replace `your-api-key` with your actual OpenAI API key.

   **Note:** The `.env` file is not included in the repository and should be created manually.

## Usage

1. Run the Streamlit app:

   ```shell
   streamlit run translate_app.py
   ```

2. The app will open in your browser. Enter the English text you want to translate in the input text area.

3. Click the "Translate" button to initiate the translation.

4. The translated text in German will be displayed below.

## Concept

The English to German Translation App leverages the power of the GPT-3.5-turbo model from OpenAI to provide accurate and context-aware translations. The app uses the Streamlit framework to create a user-friendly interface for entering the English text and displaying the translated output. The translation process is handled by making API calls to the OpenAI API and processing the response to extract the translated text.

Feel free to explore and experiment with different English texts to see how the GPT-3.5-turbo model performs in translating them to German.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
