# Weather Patterns and Malaria Incidence in Nigeria

**Author:** Dorathy Ugwuoke  
**Course:** Data Analysis and Visualization (3MTT NextGen)

## Project Overview

This project explores the relationship between selected weather variables — rainfall, temperature, and humidity — and malaria incidence across five selected Nigerian states: FCT, Nasarawa, Niger, Kogi, and Kaduna.

The aim is to identify patterns and correlations that may provide useful insights for malaria monitoring and public health planning.

## Problem Statement

Malaria outbreaks are often linked to environmental conditions, but these patterns are not always clearly analyzed using data. This project applies data analysis and visualization to explore the relationship between weather conditions and malaria incidence in selected Nigerian states.

## Objectives

- Analyze the relationship between rainfall, temperature, humidity, and malaria incidence.
- Identify patterns and correlations across the selected states.
- Highlight weather variables with stronger relationships to malaria incidence.
- Explore how the findings could support future malaria risk prediction and public health planning.

## States Analyzed

- Federal Capital Territory (FCT)
- Nasarawa
- Niger
- Kogi
- Kaduna

## Dataset

### Variables
- Malaria Cases
- Rainfall
- Temperature
- Humidity

### Data Sources
- **Malaria incidence data:** National Bureau of Statistics (NBS)
- **Weather data:** Nigerian Meteorological Agency (NiMet)

## Tools

- Google Sheets
- Data visualization
- Streamlit (interface/prototype)

## Methodology

1. Data collection
2. Data cleaning and processing
3. Correlation analysis
4. Data visualization
5. Interpretation of findings

## Key Findings

The correlation analysis produced different patterns across the selected states:

| State | Temperature Correlation | Rainfall Correlation | Humidity Correlation |
|---|---:|---:|---:|
| Kogi | -0.474 | -0.265 | 0.083 |
| FCT | -0.022 | -0.004 | 0.461 |
| Niger | 0.775 | -0.220 | 0.168 |
| Kaduna | -0.064 | -0.400 | 0.551 |
| Nasarawa | 0.110 | -0.055 | 0.104 |

### Key observations

- **Niger State** recorded the strongest positive correlation between temperature and malaria cases (**r = 0.775**).
- **Kaduna** recorded the strongest positive humidity correlation (**r = 0.551**).
- **FCT** also showed a moderate positive relationship between humidity and malaria (**r = 0.461**).
- **Kogi** showed a moderate negative correlation between temperature and malaria (**r = -0.474**).
- **Nasarawa** showed weak correlations across the weather variables.

These results describe associations in the analyzed data and should not be interpreted as proof of causation.

## Key Visualizations

### 1. Temperature vs Malaria — Niger

The project visualization highlights the strong positive correlation between temperature and malaria cases in Niger State.

![Temperature vs Malaria](visuals/temperature_vs_malaria.png)

### 2. Humidity vs Malaria — Kaduna

The second key visualization highlights the relationship between humidity and malaria incidence in Kaduna.

![Humidity vs Malaria](visuals/kaduna_humidity_vs_malaria.png)

> Add the final chart images to the `visuals` folder using the filenames above.

## Streamlit Interface

I collaborated with a UI/UX expert to design the interface for how the project could be presented as an application.

**Demo:** Add your Streamlit/demo link here.

## Potential Impact

The analysis could support:

- Better malaria risk monitoring and prediction
- Smarter resource allocation
- Improved public health planning

## Recommendation / Future Work

If the project receives further support, I would like to develop a predictive model that can better estimate malaria risk using weather variables and provide useful insights for public health decision-making.

Future development could include additional environmental and health variables, a larger dataset, and machine-learning techniques.

## Conclusion

This project shows that the relationship between weather variables and malaria incidence differs across the selected Nigerian states. Temperature showed the strongest positive relationship in Niger, while humidity showed stronger positive relationships in Kaduna and FCT.

The findings demonstrate how data analysis and visualization can help uncover patterns that may be useful for future malaria risk prediction and public health planning.

## Project Files

```text
weather-malaria-nigeria/
├── README.md
├── data/
│   └── malaria_weather_data.csv
├── analysis/
│   └── correlation_summary.csv
├── visuals/
│   ├── temperature_vs_malaria.png
│   └── kaduna_humidity_vs_malaria.png
└── presentation/
    └── project_presentation.pdf
```

