# NSPC (Number of Strokes Per Character)

This is the source code for brief report 'Complexity of Chinese given names: a simple
indicator of achievements across fields from ancient to modern China'.

# Abstract 
Using three large-scale datasets spanning over 1,400 years, we find that the complexity of Chinese given names, quantified by the number of strokes per character (NSPC), indicates one’s achievements in income, education, entrepreneurship, and official careers. We observe significant correlation between the parents’ education/income levels and the children’s NSPC, suggesting that parents’ socioeconomic resources play an important part in this relationship. The simple quantification aided by NSPC allows researchers to discern patterns that carry socioeconomic implications. To the extent that children’s names are a form of family
cultural resources, NSPC is an important measurement and source of class-based advantage. Furthermore, NSPC allows us to identify industry stratification in China and track its evolution over time. We show that NSPC can complement the huge amount of data containing Chinese names and furthers existing understanding of family resources, class structure and social stratification in China.

# Repository Description

This repository contains code for generating Figure 1 in the brief report. Figure 1 is a figure with multiple subplots, illustrating various aspects of the data analysis, using Jupyter Notebook.

## Prerequisites

The code has been successfully tested in the following environment.

* python 3.7.2
* pandas: 2.0.3
* numpy: 1.24.3
* matplotlib: 3.7.2
* IPython          : 8.12.2
* ipykernel        : 6.25.2
* jupyter_client   : 8.1.0
* jupyter_core     : 5.3

## Usage

The notebook contains multiple cells, each representing the plotting function for subplots B to H. Execute the cells to generate the plots. The final figure `combination.pdf` will be saved in the `fig` directory.

Before running `draw_fig.ipynb`, make sure you have the required CSV files in the `data` directory and the `colors_19.json` file in the `fig` directory. 

The descriptions of each CSV file are recorded in the cell descriptions of the Jupyter Notebook. These files have undergone preprocessing and contain statistical information. They do not include any personal privacy and can be directly used for plotting.

## Additional Files

- `colors_19.json`: A JSON file containing pre-defined color schemes for Figure(B)'s industry visualization.
- `A.png`: An image file that should be manually placed in the figure after generating `combination.pdf`. This image serves as a placeholder and should be flattened into the PDF for the final figure.
