# Data Visualization with Dimensionality Reduction

This project uses **dimensionality reduction algorithms (UMAP, PCA, MDS)** to analyze and visualize data from multiple columns, with the goal of **examining the behavior and correlation of the input data**. The code is divided into three Jupyter Notebooks, each dedicated to a specific visualization.

## Content

- General Description
- Requirements
- Execution
- Description of the Notebooks
- Contribution
- License
  
## General Description
The objective of this project is to reduce the dimensionality of a dataset using UMAP, PCA, or MDS, and then visualize the results in different ways. The data is read from a CSV file and processed to generate three types of plots:

**Trajectory Plot**: Displays the reduced data grouped by categories, with each point labeled according to its date and connected by smooth trajectories.  
**Hexagon Plot with Data Expansion**: Generates hexbin plots by category, expanding the data using a meshgrid to fill in missing information.  
**Combination of Hexagons and Trajectories**: Combines the hexagon visualization with expanded information and point trajectories.  

## Requirements  

For the project to function correctly, it is necessary to have the required libraries. To do this, you need to use the **requirements.txt** file and enter the following command in the terminal of your working environment:  

**pip install -r requirements.txt**

## Execution

Each visualization is in a separate Jupyter Notebook. To run them, place the CSV data file inside the folder where the notebooks are located and specify the file name as well as its format. Each Notebook has its own functions with respective parameters that can be modified according to the desired outcome, and the generated plots will be displayed at the end.

## Description of the Notebooks

- **Trajectory Plot (GraficoDeTrayectorias.ipynb)**
This notebook reduces the dimensionality of the data, groups the results by categories, and plots the points with date labels. The trajectories between points are displayed using CubicSpline.

- **Hexagon Plot with Data Expansion (GraficoPorCategorias.ipynb)**
This notebook plots a hexbin by category, coloring the hexagons based on the number of points they represent. Then, a meshgrid is used to expand the data and assign values to hexagons without original information.

- **Combination of Hexagons and Trajectories (GraficoTrayectoriasCategorias.ipynb)**
This notebook combines the hexagons generated in the second notebook with the point trajectories and date labels for each category, offering a more comprehensive visualization.

## Contribution  
**Diseño y programación**: *Leonardo Vázquez-Rodríguez*  
**Diseño**: *José-Luis Jiménez-Andrade, Humberto-Andrés Carrillo-Calvet*  

## License
*MIT License*  

*Copyright (c) [2024] [Gráficos de trayectorias]*  

*Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:*

*The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.*

*THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.*
