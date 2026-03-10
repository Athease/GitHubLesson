# SUGMA NUTS BRO

A reproducible analysis of morphological measurements from the Palmer Penguins dataset, examining variation in body dimensions across penguin species in the Palmer Archipelago, Antarctica.

<img src="https://i.pinimg.com/736x/9c/67/38/9c6738bf74f94adf5ed0f9e4170cbf2d.jpg" width=50%>


6767676767676767676767676767676767676767


| `flipper_length_mm` | 172.0-231.0 |
| `body_mass_g` | 2700-6300 |

## What the Analysis Does ehehehahahah

The R script `run_analysis_SOLUTIONS.R` performs the following steps:

1. **Data cleaning** -- removes some the NAs and creates a new object containing the cleaned daa 
2. **Exploratory boxplots** -- makes some box plots of all of the data in order to explore the variation visually. No stats at this point
3. **Cluster analysis** -- [TODO: Which two measurements are used to show how species cluster? Hint: look at section 7]
4. **Regression analysis** -- [TODO: What relationship does the regression plot examine? Hint: look at section 7]

## Plots Produced

The analysis generates a multi-panel figure combining four plots:

- **Top left:** [TODO: What does this plot show?]
- **Top right:** [TODO: What does this plot show?]
- **Bottom left:** [TODO: What does this plot show?]
- **Bottom right:** [TODO: What does this plot show?]

## Project Structure

```
penguin-analysis/
├── README.md              ← You are here!
├── .gitignore             ← [TODO: What does a .gitignore file do?]
├── data/
│   └── penguins_raw.csv   ← [TODO: Describe this file in one sentence]
├── functions/
│   ├── plotting_functions.R  ← [TODO: Describe what this file contains]
│   └── saving_functions.R    ← [TODO: Describe what this file contains]
└── run_analysis_SOLUTIONS.R  ← [TODO: Describe what this file does]
```

## How to Run

1. Open `run_analysis_SOLUTIONS.R` in RStudio
2. Install required packages: `tidyverse`, `janitor`, `palmerpenguins`, `patchwork`
3. Run the script from top to bottom
4. Outputs are saved to the `figures/` folder

## Data Source

Horst AM, Hill AP, Gorman KB (2020). *palmerpenguins: Palmer Archipelago (Antarctica) penguin data.* R package version 0.1.0. https://allisonhorst.github.io/palmerpenguins/

## Authors

[TODO: Add your name here! This is a great first commit.]


