# Data Science Mini-Portfolio

This repository was prepared to present my data science coursework in a **clear and reproducible way, without the feel of homework submissions**. The **code cells remain untouched**; only the notebook (Markdown) texts containing “homework/assignment/points” were rewritten into project-appropriate descriptions.

## Contents

| Folder / File | Description | How to Run / Notes |
|---|---|---|
| **01-temporal-energy-analysis/** | Exploratory Data Analysis (EDA) notebook on global energy consumption. | Unzip the `World Energy Consumption.csv.zip` file in the same folder and place **`World Energy Consumption.csv`** next to the notebook. |
| **02-homework-1/** | An independent analysis notebook originally from the first homework set (homework references removed). | Open with `jupyter notebook`. |
| **03-term-project-team/** | **Team project**: notebook + presentation. | Teammate: **Hasan Kan**. Presentation: `term-project-presentation.pptx` – Video link: `term-project-youtube-link.txt`. |
| **04-streamlit-whisper-ner-legacy/** | Archive of an older Streamlit app (Whisper ASR + NER). | Provided for reference. |
| **requirements.txt** | Required Python packages. | See the “Setup” section below. |

## Setup

    python -m venv .venv
    source .venv/bin/activate   # On Windows: .venv\Scripts\activate
    pip install --upgrade pip
    pip install -r requirements.txt

## Running the Notebooks

    jupyter notebook  # or jupyter lab

- **Data access:** The **CSV** in `01-temporal-energy-analysis/` is compressed. Extract `World Energy Consumption.csv.zip` and place `World Energy Consumption.csv` in the same folder. If the filename changes, update the path in the notebook accordingly.

## Notes
- The team project folder explicitly indicates collaboration details.

## License
Code: **MIT**. Dataset licenses may vary depending on their source.
