# Installation & Usage

## Requirements

Make sure Python 3.10+ is installed.

Install all dependencies:

```bash
pip install -r requirements.txt
```

## Running the Project

Start the application by running:

```bash
python main.py
```

If using Streamlit directly:

```bash
streamlit run app.py
```

## Project Workflow

1. User submits a city complaint through the interface
2. NLP pipeline preprocesses the text
3. Machine Learning model classifies complaint category
4. Urgency prediction model evaluates severity
5. System assigns priority score
6. Dashboard updates analytics and visualizations
7. System recommends the responsible municipal department

## Technologies Used

* Python
* Scikit-learn
* Pandas
* NumPy
* Streamlit
* Plotly
* Machine Learning
* Natural Language Processing (NLP)

Built for SmartScape Hackathon 2026.
