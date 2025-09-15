# Team Pressing Analysis

This repository contains the **team_pressing.ipynb** notebook, which analyzes soccer team pressing metrics to gain insights into defensive intensity, patterns of ball recovery, and opponent disruption.

## 📂 Project Overview
The goal of this notebook is to:
- Load and clean match-event data (e.g., from StatsBomb or similar sources).
- Quantify pressing actions across teams and players.
- Visualize key metrics like pressing efficiency, pressure zones, and time-to-press.

## 🛠️ Features
- **Data Cleaning & Preprocessing:** Handles raw match-event data for accurate analysis.
- **Exploratory Data Analysis:** Visualizes pressing patterns using heatmaps and possession-based stats.
- **Custom Metrics:** Calculates pressing intensity (PPDA) and other advanced soccer analytics metrics.
- **Interactive Visualizations:** Generates plots to highlight team and player performance.

## 📋 Requirements
To run the notebook, you’ll need:

- Python 3.9+
- Jupyter Notebook or JupyterLab
- Common data-science libraries:
  ```bash
  pip install pandas numpy matplotlib seaborn scikit-learn
  ```
- (Optional) Plotting/visualization:
  ```bash
  pip install plotly
  ```

## 🚀 Usage
1. Clone this repository:
   ```bash
   git clone git@github.com:Yashuchirag/team_pressing_project.git
   cd team-pressing
   ```
2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Open and run the cells in **team_pressing.ipynb**.

## 📊 Data
- Input data should be match-event data in CSV/JSON format.
- Update the notebook’s data-loading cell with the correct path to your dataset.

## 📈 Outputs
- Pressing intensity charts
- Heatmaps of defensive actions
- Team-wise and player-wise pressing statistics

## 🧑‍💻 Author
- **Chirag Chandrashekar**  
  [GitHub](https://github.com/Yashuchirag) • [LinkedIn](https://www.linkedin.com/in/chirag-chandrashe-15b965103/)
- **Viveka Salinamakki**
  [GitHub](https://github.com/vsg-vsg) • [LinkedIn](https://www.linkedin.com/in/viveka-salinamakki-896387191/)
- **Chris Alexander**
  [GitHub](https://github.com/ChrisAlex2104) • [LinkedIn](https://www.linkedin.com/in/chris-thomas-alexander/)

> ⚽ *This notebook is designed for analysts, data scientists, and football enthusiasts who want to explore and quantify team pressing behaviors.*
