# Airline Data Visualisation

A Python data-visualisation project exploring airline passenger patterns across travel classes and time. The repository includes Jupyter analysis, a supporting FFT utility, exported visualisations and a written report.

## Project focus

The notebook compares passenger volumes across Economy and Business classes and uses a Fourier-transform-based smoothing approach to explore broad patterns in the time series.

## Repository contents

- Jupyter notebook(s) containing the analysis and visualisation workflow
- `scrfft.py` — a helper function for interpolating data and calculating real FFT components
- Dataset files used by the notebook
- Exported chart images and PDF report

## Technology

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Jupyter Notebook
- NumPy FFT

## Run the analysis

1. Clone the repository:

   ```bash
   git clone https://github.com/UtsavChalodiya/Airline-Data-Visulization.git
   cd Airline-Data-Visulization
   ```

2. Create and activate a virtual environment:

   ```bash
   python -m venv .venv
   # Windows
   .venv\Scripts\activate
   # macOS / Linux
   source .venv/bin/activate
   ```

3. Install the main dependencies:

   ```bash
   pip install numpy pandas matplotlib seaborn jupyter
   ```

4. Open the notebook in Jupyter and run the cells in order. Ensure the input datasets are present at the paths referenced by the notebook.

## Interpretation notes

FFT smoothing is a visual technique for exploring broad patterns; it should not be interpreted as a forecast without additional validation. Document the data source, date coverage, units and any transformations when presenting the findings.

## Author

**Utsav Chalodiya**  
[GitHub profile](https://github.com/UtsavChalodiya)
