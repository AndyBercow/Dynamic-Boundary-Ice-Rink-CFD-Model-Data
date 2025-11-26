# Dynamic-Boundary-Ice-Rink-CFD-Model-Data

CFD dataset for a generalized ice rink model with dynamic boundary conditions. Includes simulation data (ice surface temperatures, grid exports) from STAR-CCM+ and processed input parameters (meteorological time-series, occupancy) generated with MATLAB. Supports the development and validation of thermodynamic models for indoor ice rinks.

## Research Overview
This dataset supports a computational fluid dynamics (CFD) study investigating the thermal environment in an ice rink under various dynamic boundary conditions. The research focuses on the interplay between environmental factors (external temperature, solar radiation) and occupancy patterns, and their collective impact on ice surface temperature distribution.

## Data Description
The dataset is organized into the following files:

### Core Simulation Results (STAR-CCM+ Outputs)
- **`IceSurfaceTemp_3DField_DynamicPopulation_DynamicEnvelope.xlsx`**: 3D temperature field with dynamic population and dynamic building envelope conditions.
- **`IceSurfaceTemp_3DField_StaticPopulation_DynamicEnvelope.xlsx`**: 3D temperature field with static population and dynamic building envelope.
- **`IceSurfaceTemp_3DField_DynamicPopulation_StaticEnvelope.xlsx`**: 3D temperature field with dynamic population and static building envelope.
- **`IceSurfaceTemp_3DField_StaticPopulation_StaticEnvelope.xlsx`**: Baseline 3D temperature field with static population and static envelope.

### Reference & Validation Data
- **`ReferenceDataset_IceRink_IceSurfaceTemp_TheoreticalBaseline.xlsx`**: Theoretical baseline ice surface temperatures for model validation.
- **`ComparativeDataset_IceRink_IceSurfaceTemp_SmithsModel.xlsx`**: Ice surface temperature data from Smith's model for comparative analysis.
- **`Beijing_IceRink_Temperature_PredictedVsMeasured_WithError.xlsx`**: Comparison between predicted and measured temperatures with error analysis.

### Occupancy & Population Data
- **`MicroscopicSimulation_SFM_OccupancyDistribution.xlsx`**: Occupancy distribution from Social Force Model microscopic simulation.
- **`IceStadium_Simulated_PopulationDensity-Count_Theoretical.xlsx`**: Theoretical population density and count data for the ice stadium.

### Meteorological & Environmental Inputs
- **`Beijing_SummerHighTemp_Hourly_FromJuly1.xlsx`**: Hourly high-temperature data for Beijing summer starting July 1st.
- **`Beijing_ForlceRink_TotalRadiation(Incl-Scattered)_Hourly.xlsx`**: Hourly total radiation data (including scattered radiation) for the ice rink location.
- **`Beijing_Meteorology_Temp-Wind-Radiation_TimeSeries.xlsx`**: Comprehensive time-series meteorological data (temperature, wind, radiation).

## Data Format
All data files are provided in **Microsoft Excel (.xlsx) format**.

- **Advantage**: This format is ideal for direct viewing, manual inspection, and creating plots using spreadsheet applications (like Microsoft Excel or Google Sheets).
- **Compatibility**: The data can be easily imported into various programming environments (e.g., MATLAB, Python with pandas, R) for further analysis. Most scientific data analysis tools provide straightforward functions for reading .xlsx files.

## Usage Notes
- This dataset is provided "as is" without warranty of any kind. It was generated for the specific research purposes described in the associated manuscript and may contain uncertainties or limitations inherent to the simulation and measurement methods.
- Users are encouraged to validate the data for their own specific applications.
- When using this dataset, please cite both the dataset itself and the associated research paper.

## License
This dataset is licensed under the MIT License. See the LICENSE file in this repository for details.

## Contact
For questions regarding this dataset, please contact Yuhan.G at 15688987209@163.com.
