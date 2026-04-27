# 🎮 Video Game Sales Analysis (1980-2020)

[![Kaggle](https://img.shields.io/badge/Kaggle-Data-blue?logo=kaggle)](https://www.kaggle.com/datasets/gregorut/videogamesales)
[![Python](https://img.shields.io/badge/Python-3.8+-green?logo=python)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 📊 Project Overview

A comprehensive Exploratory Data Analysis (EDA) of video game sales data spanning over 16,500 games from 1980 to 2020. This project examines sales patterns, regional preferences, genre performance, and platform trends to uncover insights about the global video game market.

## 📈 Key Findings

### 1. **North America Dominates the Market**
- North America accounts for **~49%** of global video game revenue
- Europe follows with ~27%, Japan with ~14%
- Strategic implication: Publishers should prioritize NA market for maximum ROI

### 2. **Top-Selling Games of All Time**
| Rank | Game | Global Sales (Millions) |
|------|------|------------------------|
| 1 | Wii Sports | 82.74 |
| 2 | Super Mario Bros. | 40.24 |
| 3 | Mario Kart Wii | 35.82 |
| 4 | Wii Sports Resort | 33.00 |
| 5 | Pokemon Red/Blue | 31.37 |

### 3. **Genre Performance**
- **Action** and **Sports** genres generate the highest total revenue
- Role-Playing games dominate the Japanese market
- Shooter games perform exceptionally well in North America

### 4. **Industry Peak (2007-2010)**
- Peak game releases coincided with Wii, PS3, and Xbox 360 launch
- Market saturation observed post-2010
- Shift toward digital/mobile platforms not captured in this dataset

### 5. Regional Preferences

### Key Regional Insights

**🇺🇸 North America (49% Market Share)**
- Largest gaming market globally
- Shooter and Action genres dominate
- Strong preference for Western-developed titles
- Holiday season (Nov-Dec) drives 40% of annual sales

**🇪🇺 Europe (27% Market Share)**
- Second largest market
- Action and Sports genres lead
- Strong racing game culture (Formula 1, Rally)
- FIFA franchise performs 2x better here than in NA

**🇯🇵 Japan (14% Market Share)**
- Unique market preferences
- Role-Playing Games (RPGs) are king
- Strong mobile and handheld gaming culture
- Nintendo dominates local market share
- Different sales patterns - steady year-round, no holiday spike

**🌍 Other Regions (10% Market Share)**
- Growing markets: South America, Asia-Pacific
- Mobile gaming leading growth
- Price sensitivity higher than established markets

## 💡 Business Insights

### Key Takeaways from Analysis

| Focus Area | Insight | Action Item |
|------------|---------|-------------|
| **North America** | 49% of global sales | Allocate 50% of budget here |
| **Top Genres** | Action + Sports = Highest ROI | Invest in these categories |
| **Peak Timing** | 2007-2010 golden era | Study successful titles from this period |
| **Japan Market** | RPG + Nintendo dominate | Partner with local studios |
| **Platform** | PS2, Wii, Xbox 360 top performers | Consider remasters for these platforms |

### Strategic Recommendations

1. **Market Entry**: Launch in NA first, then EU, then JP
2. **Genre Focus**: Action games offer best risk-to-reward ratio
3. **Timing**: Q4 releases in NA, Q2 releases in EU
4. **Localization**: Full translation for JP, partial for EU
5. **Pricing**: Tiered pricing ($70 NA, $60 EU, $50 JP)

## 🛠️ Technologies Used

### Core Libraries
| Library | Version | Purpose |
|---------|---------|---------|
| **Python** | 3.8+ | Core programming language |
| **Pandas** | 1.3+ | Data manipulation & analysis |
| **NumPy** | 1.21+ | Numerical operations |
| **Matplotlib** | 3.4+ | Data visualization |
| **Seaborn** | 0.11+ | Statistical visualizations |

### Development Environment

- **Jupyter Notebook** - Interactive development
- **Kaggle** - Dataset source & initial development

### Key Python Packages Used
```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
