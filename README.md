# Global Development Analytics

A concise exploratory analysis of global development indicators using the Gapminder dataset (1952–2007). The project contains a Jupyter notebook with data cleaning, analysis, and visualizations exploring life expectancy, GDP per capita, and population trends.

---

## Table of Contents

- [Dataset](#dataset)
- [Files](#files)
- [Quick Start](#quick-start)
- [Usage](#usage)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)

---


## Dataset

Gapminder — Life Expectancy, GDP per Capita & Population (1952–2007). Key points:

- ~142 countries
- Data every 5 years from 1952 to 2007
- Variables: `lifeExp`, `gdpPercap`, `pop`, `country`, `year`, `continent`

---

## Files

- [gapminder.csv](gapminder.csv) — dataset CSV
- [Global_Development_Analytics.ipynb](Global_Development_Analytics.ipynb) — analysis notebook with visualizations and commentary

---

## Quick Start

Prerequisites:

- Python 3.8+ (3.10+ recommended)
- pip

Install common dependencies:

```bash
pip install --upgrade pip
pip install pandas numpy matplotlib seaborn plotly jupyterlab
```

---

## Usage

Open and run the analysis notebook locally:

```bash
jupyter lab Global_Development_Analytics.ipynb
```

Or run the notebook non-interactively and export HTML:

```bash
jupyter nbconvert --to html Global_Development_Analytics.ipynb
```

---

## Examples

- Visualize life expectancy vs GDP per capita over time by continent.
- Plot population growth for selected countries.
- Compare time-series for life expectancy across regions.

See the notebook for code snippets and plots.

---

## Contributing

Contributions welcome — open an issue or submit a pull request. Suggested contributions:

- Improve visualizations or notebook narration
- Add reproducible scripts to regenerate figures
- Add a `requirements.txt` or `environment.yml` for reproducible environments

---

## License

If you want to license this repository, add a `LICENSE` file. Gapminder data is publicly available; verify any external dataset terms before redistribution.

---

## Contact

For questions or suggestions, please open an issue.
