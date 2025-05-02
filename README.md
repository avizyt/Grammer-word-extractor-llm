# Gemini Grammer Word Extractor LLM

**Grammer Word Extractor LLM** is a Python-based tool designed to extract grammatical words from textual data using Large Language Models (LLMs). This utility aids in identifying and analyzing grammatical components within text, facilitating linguistic research and natural language processing tasks.

## Features

- **LLM Integration**: Leverages the capabilities of large language models to accurately extract grammatical words.
- **JSON Vocabulary Support**: Utilizes customizable JSON files (`vocabulary1.json`, `vocabulary2.json`) to define and manage grammatical word lists.
- **Modular Architecture**: Structured with separate modules for models, services, and main execution, promoting maintainability and scalability.

## Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/avizyt/Grammer-word-extractor-llm.git
   cd Grammer-word-extractor-llm
   ```

2. **Set Up a Virtual Environment (Optional but Recommended)**

   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```

3. **Install Dependencies**

   *(Note: A `requirements.txt` file is not present. Please ensure necessary packages are installed as per your environment.)*

   ```bash
   pip install -r requirements.txt
   ```

   *If `requirements.txt` is unavailable, manually install required packages.*

## Usage

1. **Prepare Input Data**

   Place your text data in a file named `exmple.txt` in the root directory.

2. **Execute the Main Script**

   ```bash
   python main.py
   ```

   The script will process the input text and extract grammatical words based on the vocabularies provided.

## Project Structure

```
Grammer-word-extractor-llm/
├── __pycache__/           # Compiled Python files
├── QnadA.json             # JSON file containing questions and answers
├── exmple.txt             # Sample input text file
├── main.py                # Main script to run the extractor
├── models.py              # Defines data models and structures
├── services.py            # Contains core logic for extraction
├── vocabulary1.json       # First vocabulary list of grammatical words
├── vocabulary2.json       # Second vocabulary list of grammatical words
└── .gitignore             # Git ignore file
```

## Customization

- **Updating Vocabularies**: Modify `vocabulary1.json` and `vocabulary2.json` to include or exclude specific grammatical words as per your requirements.

- **Input File**: Replace `exmple.txt` with your own text file to analyze different content.

## Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to fork the repository and submit a pull request.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

MIT
