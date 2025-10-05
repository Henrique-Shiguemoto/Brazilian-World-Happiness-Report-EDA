# World Happiness Brazilian Report Analysis

This is an analysis of the World Happiness report published at: [World Happiness Report](https://www.worldhappiness.report/).

The objective is to analyze Brazilian happiness data and analyze possible reasons to explain the patterns of happiness across multiple years (from 2020 to 2024).

# Data Structure

The public report data is structured in excel files. Some years have different columns, but generally speaking these are the columns from the tabular

| Column Name                                | Description                                                                                  |
|--------------------------------------------|----------------------------------------------------------------------------------------------|
| Country                                    | The name of the country                                                                      |
| Happiness score                            | Overall happiness score of the country                                                       |
| Dystopia + residual                        | Baseline happiness level (Dystopia) plus unexplained residual                                |
| Explained by: GDP per capita               | Contribution of GDP per capita to the happiness score                                        |
| Explained by: Social support               | Contribution of social support to the happiness score                                        |
| Explained by: Healthy life expectancy      | Contribution of healthy life expectancy to the happiness score                               |
| Explained by: Freedom to make life choices | Contribution of freedom to make life choices to the happiness score                          |
| Explained by: Generosity                   | Contribution of generosity to the happiness score                                            |
| Explained by: Perceptions of corruption    | Contribution of perceived corruption to the happiness score                                  |

# Technologies used:

- Python
- Pandas
- matplotlib, seaborn and plotly
- Jupyter Notebooks
- Excel