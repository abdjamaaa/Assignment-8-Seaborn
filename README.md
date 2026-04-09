# Seaborn Data Visualization Project

## Purpose
This project uses Python and Seaborn to create data visualizations from real-world exercise data and the built-in planets dataset.

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

## Technologies Used
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
Exercise data shows that pulse increases with exercise and is slightly affected by diet.  
Planets data shows that farther planets tend to have longer orbital periods.

---

## Limitations
- Assumes columns: `pulse`, `diet`, `exercise`
- Missing data may affect results

---

## Conclusion
This project shows how Seaborn can visualize patterns and relationships in data effectively.

---

## AI Usage
This project was completed with assistance from ChatGPT.
