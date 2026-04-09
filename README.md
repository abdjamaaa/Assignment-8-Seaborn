# Seaborn Data Visualization Project

## Purpose
The project is written in Python using Seaborn to generate visualizations of data through real life exercise data and the provided built in planet data set.

---

## Overview
The project includes:
- Heatmap of pulse by diet and exercise
- Categorical plot of pulse values
- Planets dataset visualizations:
  - Relational plots (scatter, line)
  - Distribution plots (histogram, KDE)
  - Categorical plots (box, bar)

---

## Libraries Used
- Python
- Pandas
- Seaborn
- Matplotlib

---

## Class Design
The program uses a class called `SeabornAssignment` to organize the code.

### Attributes
- `exercise_file`
- `exercise_data`
- `planets_data`

### Methods
- `load_data()` → loads datasets  
- `set_style()` → applies plot styling  
- `exercise_heatmap()` → creates heatmap  
- `exercise_catplot()` → creates categorical plot  
- `planets_relational_plots()` → scatter + line plots  
- `planets_distribution_plots()` → histogram + KDE  
- `planets_categorical_plots()` → box + bar plots  
- `print_explanations()` → prints conclusions  

---

## Results
Results of exercises indicate that pulse rises and is marginally influenced by diet.  
Planets data indicates that more distant planets are likely to have longer orbital periods.

---

## Limitations
- Assumes columns: `pulse`, `diet`, `exercise`
- Missing data may affect results


---

## AI Usage
This project was completed with assistance from ChatGPT.
