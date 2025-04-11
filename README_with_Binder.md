# MUST4Water: Interactive Hydrology-Economy Simulation

[![Launch Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Alek327/must4water/HEAD?filepath=must4water_interactive.ipynb)

This interactive tool simulates water demand, runoff, recharge, and sectoral extraction in a hybrid economic-hydrological system. It includes:

- 📊 Monte Carlo simulations of EWEI (Extended Water Exploitation Index)
- 🌍 Climate scenario switching (SSP2, SSP3, SSP5)
- 📂 CSV upload for real hydrological data
- 🎚️ Sliders for tuning irrigation efficiency, groundwater/surface water shares, and more

## Getting Started

### Installation

Clone the repository and install the required packages:

```bash
git clone https://github.com/Alek327/must4water.git
cd must4water
pip install -r requirements.txt
```

### Run the Notebook

Start Jupyter Notebook and open:

```
must4water_interactive.ipynb
```

Or launch online with Binder:

👉 [Open in Binder](https://mybinder.org/v2/gh/Alek327/must4water/HEAD?filepath=must4water_interactive.ipynb)

## Files

- `must4water_interactive.ipynb` – Main interactive simulation
- `must4water_model.py` – Core calculation functions (optional use)
- `hydrology_input.csv` – Sample input data for 2010–2020
- `requirements.txt` – Python dependencies

## License

MIT License