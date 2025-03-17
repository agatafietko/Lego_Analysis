# 🧱 Lego Set Analysis: Trends & Insights (1980-2022)

<div align="center">
  <img src="https://github.com/agatafietko/Lego_Analysis/blob/main/img/lego_banner.jpg" alt="Lego Banner" width="800"/>
</div>

[![GitHub last commit](https://img.shields.io/github/last-commit/agatafietko/Lego_Analysis)](https://github.com/agatafietko/Lego_Analysis/commits/main)
[![GitHub repo size](https://img.shields.io/github/repo-size/agatafietko/Lego_Analysis)](https://github.com/agatafietko/Lego_Analysis)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?style=flat&logo=Jupyter)](https://jupyter.org/)

## 📋 Table of Contents
- [Project Overview](#-project-overview)
- [Interactive Notebook](#-interactive-notebook)
- [Analyses Performed](#-analyses-performed)
- [Key Visualizations](#-key-visualizations)
- [Data Source](#-data-source)
- [Requirements](#-requirements)
- [Repository Structure](#-repository-structure)
- [Usage](#-usage)
- [Key Findings](#-key-findings)
- [Future Work](#-future-work)
- [Author](#-author)
- [License](#-license)
- [Acknowledgments](#-acknowledgments)

## 🔍 Project Overview

This project analyzes the comprehensive Rebrickable Lego dataset to uncover trends and patterns in Lego set releases, piece counts, themes, and pricing over the past four decades (1980-2022). The analysis explores how the Lego product line has evolved over time, identifies the most popular themes, and examines the relationships between various set characteristics.

<div align="center">
  <img src="https://github.com/agatafietko/Lego_Analysis/blob/main/img/visualization_images/theme_evolution.png" alt="Lego Theme Evolution" width="600"/>
  <p><i>Evolution of Lego themes over time</i></p>
</div>

## 📊 Interactive Notebook

The [`Lego(1).ipynb`]([https://github.com/agatafietko/Lego_Analysis/blob/main/notebooks/lego_analysis.ipynb](https://github.com/agatafietko/Lego_Analysis/blob/main/Lego(1).ipynb)) notebook contains all the code and fully rendered visualizations. You can view this notebook directly on GitHub to see all the charts and analysis without having to run any code. The notebook features:

- 📝 Detailed markdown explanations before each analysis section
- 💻 Well-commented code with clear variable naming
- 🎨 All visualizations rendered inline with colorful, Lego-themed visualization schemes
- 🖱️ Interactive plots where applicable (hover for details)
- 🧹 Comprehensive data cleaning and preprocessing steps

## 📈 Analyses Performed

1. **Historical Trends in Lego Set Releases**
   - Year-by-year analysis of set release volumes
   - Identification of key growth periods and market trends
   - Correlation with major corporate events and strategy shifts

2. **Piece Count Evolution**
   - Analysis of average piece count trends over 40+ years
   - Theme-based piece count comparisons
   - Identification of the most complex sets by decade

3. **Theme Popularity Analysis**
   - Visualization of most popular Lego themes by set count
   - Temporal analysis of theme introductions and retirements
   - Comparative study of licensed vs. original Lego IP themes

4. **Price Analysis by Theme**
   - Price per piece analysis across themes and years
   - Premium pricing identification for specialized themes
   - Historical price trends adjusted for inflation

5. **Correlation Analysis**
   - Statistical correlation between price, piece count, and popularity
   - Multiple regression analysis to identify pricing factors
   - Outlier identification and case studies

6. **Minifigure Trends**
   - Historical analysis of minifigure inclusion rates
   - Theme-specific minifigure distribution
   - Special minifigure impact on set pricing and popularity

## 🎨 Key Visualizations

All visualizations in the notebook feature:

- **Lego-inspired color palette**: Vibrant colors that reflect the Lego brand aesthetic
- **Clear annotations**: Meaningful labels, titles, and captions that explain insights
- **Consistent styling**: Professional appearance across all visualizations
- **Appropriate chart types**: Selection of the most effective visualization for each analysis question
- **Interactive elements**: Hover-over details and selectable legends where applicable

<div align="center">
  <table>
    <tr>
      <td><img src="https://github.com/agatafietko/Lego_Analysis/blob/main/img/visualization_images/sets_by_year.png" width="400"/></td>
      <td><img src="https://github.com/agatafietko/Lego_Analysis/blob/main/img/visualization_images/avg_pieces_by_theme.png" width="400"/></td>
    </tr>
    <tr>
      <td align="center"><i>Set Releases by Year</i></td>
      <td align="center"><i>Average Piece Count by Theme</i></td>
    </tr>
  </table>
</div>

The main visualizations include:
- `sets_by_year.png`: Line chart showing the trend of set releases over time
- `avg_pieces_by_theme.png`: Bar chart of average piece count across popular themes
- `theme_distribution.png`: Pie chart showing the distribution of sets across themes
- `price_vs_pieces.png`: Scatter plot analyzing the relationship between price and piece count
- `minifigures_by_theme.png`: Visualization of minifigure count trends across themes
- `theme_evolution.png`: Area chart showing how themes have evolved in popularity over decades

## 📚 Data Source

The data used in this analysis is from the [Rebrickable Lego Database](https://rebrickable.com/downloads/), which provides comprehensive information about Lego sets, parts, minifigures, and themes dating back to the 1950s. The database includes:

- 17,000+ sets
- 30,000+ parts
- 1,200+ themes
- 10,000+ minifigures
- Comprehensive metadata including release years, prices, and set relationships

## 💻 Requirements

- Python 3.6+
- Required packages:
  ```
  numpy>=1.20.0
  pandas>=1.3.0
  matplotlib>=3.4.0
  seaborn>=0.11.0
  plotly>=5.3.0
  scipy>=1.7.0
  ipywidgets>=7.6.0
  ```

You can install all requirements using:
```bash
pip install -r requirements.txt
```

## 📁 Repository Structure

```
Lego_Analysis/
├── data/                           # Dataset files
│   ├── sets.csv                    # Main sets data
│   ├── themes.csv                  # Theme information
│   ├── colors.csv                  # Color information
│   ├── parts.csv                   # Parts catalog
│   └── inventory.csv               # Set inventories
├── img/                            # Images for README and visualizations
│   ├── lego_banner.jpg             # Repository banner image
│   └── visualization_images/       # Output visualizations from analysis
├── notebooks/                      # Jupyter notebooks
│   └── lego_analysis.ipynb         # Main analysis notebook
├── scripts/                        # Helper scripts
│   ├── data_cleaning.py            # Data preparation functions
│   └── visualization_helpers.py    # Custom visualization functions
├── .gitignore                      # Git ignore file
├── LICENSE                         # MIT license file
├── README.md                       # This file
└── requirements.txt                # Python dependencies
```

## 🚀 Usage

### Viewing the Analysis
1. **View the notebook on GitHub**: 
   - The notebook has all visualizations pre-rendered for easy viewing
   - Simply click on [`lego_analysis.ipynb`](https://github.com/agatafietko/Lego_Analysis/blob/main/notebooks/lego_analysis.ipynb) in the repository

### Running the Analysis Locally
1. **Clone the repository**:
   ```bash
   git clone https://github.com/agatafietko/Lego_Analysis.git
   cd Lego_Analysis
   ```

2. **Install requirements**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the notebook**:
   ```bash
   jupyter notebook notebooks/lego_analysis.ipynb
   ```

## 🔑 Key Findings

- **Market Growth**: Lego has significantly increased its yearly set releases since the early 2000s, with a notable acceleration after 2010
- **Set Complexity**: The average piece count per set has steadily increased over time, reflecting a trend toward more complex models
- **Brand Evolution**: Licensed themes (such as Star Wars, Harry Potter, and Marvel) have become increasingly important to Lego's product strategy since the late 1990s
- **Price-Piece Relationship**: There is a strong positive correlation (r=0.78) between piece count and price, but with substantial variation by theme
- **Premium Themes**: Certain themes (like Technic and Creator Expert) consistently feature higher piece counts and price points
- **Minifigure Evolution**: Minifigure inclusion has evolved from a rare feature to a standard component in most themed sets
- **Market Strategy**: Seasonal and collectible themes have shown the highest growth rate in recent years

<div align="center">
  <img src="https://github.com/agatafietko/Lego_Analysis/blob/main/img/visualization_images/price_vs_pieces.png" alt="Price vs Pieces" width="600"/>
  <p><i>Relationship between piece count and price across themes</i></p>
</div>

## 🔮 Future Work

Potential extensions to this analysis include:
- **Secondary Market**: Examining the secondary market for Lego sets and price appreciation over time
- **Color Analysis**: Analyzing the color distribution of parts across themes and time periods
- **Media Impact**: Investigating the relationship between set popularity and movie/media tie-ins
- **Complexity Analysis**: Analyzing instruction complexity and build time estimations based on piece count and set type
- **Collector Patterns**: Studying collector behavior and investment trends in the Lego market
- **International Pricing**: Comparing regional pricing differences and marketing strategies

## 👨‍💻 Author

This analysis was created by [Agata Fietko](https://github.com/agatafietko) as part of a data science project exploring the Rebrickable Lego dataset.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Rebrickable](https://rebrickable.com/) for providing the comprehensive Lego database
- The Lego Group for creating the iconic building toys that have inspired generations
- The data science community for sharing visualization best practices and analysis techniques 
