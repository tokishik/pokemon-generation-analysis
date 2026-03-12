**Pokémon Generation Stat Analysis**
Project Overview

This project analyzes Pokémon base statistics across all generations to explore how Pokémon design has evolved over time. The goal of this analysis is to investigate whether newer generations introduce stronger Pokémon and whether the distribution of offensive, defensive, and speed stats has changed throughout the series.

Using Google Sheets, the dataset was cleaned, transformed, and analyzed using pivot tables and visualizations to uncover trends in Pokémon stat design and strength distribution across generations.

This project demonstrates key data analysis skills including data cleaning, feature engineering, statistical analysis, and data visualization.

**Dataset**

The dataset contains base statistics for Pokémon across all generations, including:

• HP
• Attack
• Defense
• Special Attack
• Special Defense
• Speed
• Total Base Stat Value
• Generation

These stats represent the core attributes that determine Pokémon strength and battle performance.

**Data Cleaning Process**

The raw dataset contained several duplicate or alternate Pokémon forms that share identical base stats. To ensure accurate analysis, the following cleaning steps were performed:

• Removed duplicate forms that had identical base stats (such as cosmetic or alternate forms)
• Preserved regional variants where typing or design meaningfully differed
• Created a concatenated stat key to identify duplicate stat distributions
• Verified that Pokémon IDs and generation assignments remained correct after cleaning

This ensured the final dataset contained unique stat distributions without redundant entries that could bias the analysis.

**Feature Engineering**

Additional metrics were created to better analyze how stats are distributed among Pokémon:

Offensive Power (%)

Represents the proportion of total stats dedicated to offensive capability.

Attack + Special Attack divided by Total

Defensive Power (%)

Represents the proportion of stats allocated to survivability.

HP + Defense + Special Defense divided by Total

Speed Share (%)

Represents the portion of total stats allocated to speed.

Speed divided by Total

These normalized metrics allow comparison across generations without being skewed by differences in total stat values.

**Analysis & Visualizations**
Average Total Stats by Generation

Average Pokémon base stats increase slightly across generations. While early generations have lower average totals, later generations introduce Pokémon with somewhat higher base stat values, suggesting a gradual increase in overall power.

**Stat Trends Across Pokémon Generations**

Individual stat trends across generations remain relatively stable. While some variation exists between generations, there is no dramatic shift in how stats are distributed among HP, Attack, Defense, Special Attack, Special Defense, and Speed.

**Stat Allocation Trends**
When analyzing stat allocation as a percentage of total stats, Pokémon design remains surprisingly consistent across generations.

On average:

• ~34% of stats are allocated to offense
• ~50% of stats are allocated to defense
• ~16% of stats are allocated to speed

This suggests that while total power may increase slightly over time, the relative balance between offensive and defensive capabilities has remained stable.

**Pokémon Strength Distribution by Generation**

Examining the distribution of Pokémon by strength tier reveals that later generations introduce a greater number of high-stat Pokémon. While weaker Pokémon remain common in every generation, newer generations tend to include more powerful designs.

This supports the idea of gradual power creep across the franchise.

**Key Insights**
The analysis reveals several notable trends in Pokémon design:

• Average Pokémon base stats increase slightly in later generations
• The proportion of offensive and defensive stat allocation remains highly consistent across generations
• Speed accounts for a relatively small but stable share of total stats
• Later generations introduce a greater number of higher-stat Pokémon, indicating mild power creep

Overall, Pokémon stat design appears to maintain a consistent balance between offense and defense while gradually introducing stronger Pokémon in newer generations.

**Tools Used**
Google Sheets
Pivot Tables
Data Cleaning Techniques
Data Visualization

**Repository Contents**

pokemon-generation-analysis.xlsx
Contains the full workflow including raw data, cleaned data, and pivot table analysis.

images/
Contains exported visualizations used in this analysis.

README.md
Project documentation and explanation of findings.

**Author**
Kyle Tokishi
