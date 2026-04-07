# Heart Stroke Detection

A machine learning project for predicting heart stroke risk using various health indicators.

## Dataset

The project uses the `heart.csv` dataset containing health metrics and stroke indicators.

## Files

- `heart.ipynb`: Jupyter notebook with data exploration, preprocessing, model training, and evaluation
- `app.py`: Streamlit web application for stroke risk prediction
- `heart.csv`: Dataset file
- `requirements.txt`: Python dependencies
- `*.pkl`: Serialized model artifacts (scaler, model, columns)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ArnavAdhikary05/heart_stroke_detection
   cd heart_stroke_detection
   ```

2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

### Running the Notebook
Open `heart.ipynb` in Jupyter and run the cells to explore the data and train the model.

### Running the Web App
```bash
streamlit run app.py
```

This will start a local web server where you can input health parameters and get stroke risk predictions.

## Model

The project uses a logistic regression model trained on the heart dataset. The model includes feature scaling and preprocessing steps.

## Contributing

Feel free to fork and submit pull requests.

## License

MIT License
