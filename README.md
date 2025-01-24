# English-to-Hindi Translation Application

This project is a Streamlit-based application that allows users to input English sentences and get translations to Hindi using the Hugging Face transformers library.

## Features

- **Translation Pipeline**: Utilizes the `Helsinki-NLP/opus-mt-en-hi` model for English-to-Hindi translation.
- **User Input**: Users can input an English sentence using a text area.
- **Real-time Translation**: Translates the sentence to Hindi upon clicking the "Translate" button.

## Files

- `app.py`: Main application script that runs the Streamlit app.
- `devcontainer.json`: Configuration file for Visual Studio Code dev containers.
- `requirements.txt`: List of dependencies for the project.
- `translation.ipynb`: Jupyter notebook for translation experimentation.
- `.github/workflows/python-package.yml`: GitHub Actions workflow for continuous integration.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-repo/English-to-Hindi.git
cd English-to-Hindi
```

2. Create and activate a virtual environment:

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install the required dependencies:

```bash
pip install -r requirements.txt
```

4. Run the Streamlit app:

```bash
streamlit run app.py
```

Visit the app in your browser at `http://localhost:8501`.

## Dependencies

- `transformers`: For the translation pipeline.
- `streamlit`: To create the web app interface.
