# MUST4Water Interactive Simulation

This package includes a full hydrology-economic model (MUST4Water) with:
- Interactive sliders for climate and efficiency parameters
- Monte Carlo simulation mode
- Climate scenario switching (SSP2, SSP3, SSP5)
- Upload support for real hydrological CSV data

## How to Use

1. Install dependencies:

```
pip install -r requirements.txt
```

2. Launch the notebook:

```
jupyter notebook must4water_interactive.ipynb
```

3. Upload your CSV or run synthetic simulations.

## File List

- `must4water_interactive.ipynb`: Interactive notebook with widgets
- `must4water_model.py`: Core simulation functions (optional)
- `hydrology_input.csv`: Sample data file
