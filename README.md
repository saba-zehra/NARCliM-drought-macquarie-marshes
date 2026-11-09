# NARCliM-drought-macquarie-marshes

What Sentinel-1 shows for 2017–2019 and what NARCliM projects for the future?

The Macquarie Marshes depend on river flow, and their wet area changes strongly between dry and wet years. This research is interested in finding out how often the dry and wet conditions seen in the past may occur in the future. First, Sentinel-1 radar images were used from 2017 to 2019 to map dry conditions in the marshes, which was then compared with river gauge flow and with a drought index built from rainfall and evaporation. Second, NARCliM2.0 regional climate projections were used to count dry spells and wet pulses in the catchment for low, medium and high emissions scenarios. Since river flow also depends on dam releases and water rules, this could help demonstrate how often drought-like conditions may return and what they did to the wetland in the past.

## Repository contents

- `02_narclim_data_access.ipynb` — notebook for accessing and processing NARCliM climate data
- `outputs/` — generated plots and analysis outputs
- `.venv/` — local virtual environment for the project

## Workflow

1. Activate the project environment.
2. Open the notebook in Jupyter or VS Code.
3. Import required libraries such as `xarray`, `matplotlib`, and `climate_utils`.
4. Load the relevant NARCliM data files.
5. Inspect variables, coordinates, and time steps.
6. Apply the climate-processing steps needed for the analysis.
7. Save figures or processed outputs to `outputs/`.

## Environment setup

This project was developed using a Conda environment named `geospatial`. A typical setup is:

```bash
conda activate geospatial
pip install xarray matplotlib numpy pandas netCDF4
```

If needed, install any additional climate utilities used in the notebook, including `climate_utils`.

## Notes

- The exact data files and variables depend on the local NARCliM archive or processed netCDF files available on the system.
- The notebook is intended as a reproducible analysis workflow and may require minor adjustments depending on data naming or versions.

## License

This project is intended for research and analysis workflows. Please check the project owner’s licensing requirements before reusing or publishing the work.
