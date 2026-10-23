# NAIL COLORS PROJECT💅

My first data analysis project using Python, Pandas and data visualization.

## Goal

Explore a small dataset of nail polish colors: understand its structure, check that the data is clean, and visualize the colors and their families with graphs.

## Dataset

File:
 nail_colors_simple.csv (20 colors, 5 columns, separated by ;)

        .ref_id – reference code of the color (NC-001 to NC-020)

        .color_name – name of the shade (e.g. Burgundy, Sage Green)

        .color_family – color group (Red, Pink, Blue, etc.)

        .hex_code – hex value of the color (e.g. #800020)

        .finish – polish finish (Cream, Gloss, Matte, Sheer,Metallic)

 I also created three new columns from hex_code: r, g and b (the red, green and blue values of each color).

## Technologies

- Python

- Jupyter Notebook

- Matplotlib

- Seaborn

- Pandas

## what the Notebook Does
 . Loads and inspects the dataset
 . Converts the hex codes into RGB numbers
 . Draws a correlation heatmap of R, G and B
 . Shows the number of colors per family (bar chart)
 . Shows each color name by family (scatter plot)

## How to Run

Install the required libraries:

```bash
py -m pip install pandas seaborn matplotlib notebook
```

Open the notebook and run the cells in order:

```bash
py -m notebook nail.ipynb
```

## What I Learned

 .Loading a CSV file with Pandas (including a custom `;` separator)
 . Inspecting a dataset with `head()`, `info()`, `describe()` and `shape`
 . Checking for duplicate rows
 . Converting hex color codes into RGB numbers
 . Computing a correlation matrix and showing it as a heatmap
 . Making bar charts and scatter plots with Seaborn and Matplotlib

## Next Steps

 . Train a model to predict `color_family` from the R, G, B values
 . Add more colors to the dataset
