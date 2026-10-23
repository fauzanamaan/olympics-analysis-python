# Olympic Medalists Analysis

pandas exploration and cleaning of Olympic medal records from 1896 to 2016, ending with a pitch for a data-driven story.

**Notebook:** [M5_Olympics.ipynb](M5_Olympics.ipynb)

This is a milestone project from the Global Career Accelerator program. The scenario and data come from the program. It is not work done for any Olympic organization or news outlet.

## Context

The scenario frames the work as research for data journalism: explore the medal records, clean them, pull out facts about athletes, countries and events, and pitch a story.

## Tools and skills

- Python, pandas, Plotly Express, Jupyter
- Inspecting data and spotting missing values
- Renaming and dropping columns
- `value_counts`, `nunique`, `sort_values`, filters with several conditions
- A small function to convert centimeters to feet and inches
- Bar chart of the top countries

## Approach

1. Inspected the data: size, columns, types, missing values and medal types.
2. Cleaned it: renamed the country code and country columns and dropped the team column.
3. Answered factual questions: age range, medal counts, number of sports and events, average age, top countries.
4. Wrote a short story pitch.
5. LevelUp: counted US gold medals, listed the Games from newest to oldest, worked out the average medalist height and weight at the most recent Winter and Summer Games, and charted the top 10 countries.

## Key findings

- **39,783 medal records:** 13,372 gold, 13,116 silver and 13,295 bronze, across 66 sports and 756 events.
- **Medalists ranged from 10 to 73 years old**, with an average age of 26.
- **Of the 10 oldest medalists**, 5 won in Art Competitions and 3 in Sailing.
- **The United States leads the medal count** with 5,637, followed by Russia (3,947) and Germany (3,756). US athletes won 2,638 gold medals.
- **At the most recent Games in the data**, Winter medalists averaged 5 ft 9.04 in and 72.21 kg, and Summer medalists 5 ft 10.22 in and 73.96 kg.
- **Story pitch:** the age of medalists. The gap between the youngest and oldest is large, and the next step is to compare age ranges in the sports with the youngest and oldest medalists, using a chart to spot outliers.

## How to run

The data file is not included (see [datasets/README.md](datasets/README.md)). The notebook keeps its saved outputs, so it can be read on GitHub without running anything.

To run it yourself:

1. Place `olympics.csv` in `datasets/`.
2. Open `M5_Olympics.ipynb` in Jupyter and run the cells from the top.

Requirements: Python 3 (the notebook was saved with Python 3.10.6), pandas, plotly and Jupyter. Package versions were not recorded.

## Repo structure

```
olympics-analysis-python/
├── M5_Olympics.ipynb   analysis notebook with saved outputs
└── datasets/
    └── README.md       which data file goes here
```
