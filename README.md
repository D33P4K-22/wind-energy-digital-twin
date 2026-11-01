# Wind Energy Turbine Digital Twin & Wake Deflection

A digital twin simulation environment for wind turbine operations and wake deflection dynamics using SCADA data streams and configuration modeling.

## Project Structure

- **DigitalTwinsimulator.ipynb**: Primary digital twin execution runtime and wake deflection calculations.
- **ScadaValues.ipynb**: SCADA operational telemetry analysis and data pipeline.
- **YamlValues.ipynb**: Configuration layout parser for wind turbine setup.
- **scada_data.csv**: SCADA dataset containing wind speed, power output, and pitch parameters.
- **wind_farm.yaml**: Physical farm parameters and layout metadata.

## Key Features

- **Digital Twin Physics:** Real-time operational simulation matching physical SCADA outputs.
- **Wake Deflection Modeling:** Visualizes downstream velocity deficits and farm efficiency metrics.
- **Data Integration:** Parses static YAML layouts against dynamic operational CSV telemetry.

## Usage

```bash
pip install jupyter pandas numpy matplotlib pyyaml
jupyter notebook DigitalTwinsimulator.ipynb