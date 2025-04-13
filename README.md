# German quiz

This is a Python-based quiz application designed to help you learn German vocabulary. The application supports several quiz modes, including translation, article identification, contextual exercises, and multiple-choice exercises. Vocabulary data is loaded from an Excel file and can be filtered by level and type. The user-friendly graphical interface is built with Tkinter.

## Features

- **Multiple Quiz Modes:**
  - **Traduzione:** Identify the Italian translation of a German word.
  - **Articolo:** Determine the correct article for a German noun.
  - **Contestuale:** Complete a sentence by filling in the missing word.
  - **Opzioni Multiple:** Choose the correct translation from three options.
- **Dynamic Filtering:** Filter vocabulary by **Level** (e.g., A1.1, A1.2) and **Type** (e.g., Noun, Adj, Verb, Adv) directly from the Excel file.
- **Interactive GUI:** Built with Tkinter for a simple and interactive experience. A history panel displays per-question feedback with color-coded icons (green for correct, red for wrong).
- **Detailed Summary Report:** At the end of the quiz, a summary window shows your overall score and detailed information for each question.

## Requirements

- Python 3.x
- pandas and openpyxl

To install the required libraries, run:

```
pip install pandas openpyxl
```

## Installation

1. Clone the repository:

```
git clone https://github.com/YourUsername/quiz-tedesco.git
cd quiz-tedesco
```

2. (Optional) Create a virtual environment and activate it:

```
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

3. Install dependencies:

```
pip install -r requirements.txt
```

Or manually:

```
pip install pandas openpyxl
```

4. Make sure the folder contains the following:

- `main.py` — Python script of the quiz
- `vocaboli_verbi.xlsx` — Excel file with vocabulary
- `.gitignore` — To exclude unnecessary files
- `README.md` — This file

The Excel file should have the following columns:  
Level, Article, Singular, Plural, Type, NounClass, Translation, Example, ExampleIT

## Usage

Run the application with:

```
python main.py
```

### Inside the GUI

- Select the quiz mode (Traduzione, Articolo, Contestuale, Opzioni Multiple)
- Choose how many questions you want (up to 20)
- Optionally filter by Level and Type
- Click "Inizia Quiz" to begin
- Answer questions and get instant feedback
- At the end, view a summary with all answers and your score

## Contributing

Feel free to open an issue or submit a pull request with suggestions and improvements.

## License

This project is licensed under the MIT License.

## Contact

For questions, contact [Your Name](mailto:youremail@example.com)

