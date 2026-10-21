# NAIL COLORS PROJECT💅

My first data analysis project using Python and Pandas.

Goal
Explore a small dataset of nail polish colors and understand its structure: how many colors it contains, which columns it has, and whether the data is clean.

Dataset
File: nail_colors_simple.csv (20 colors, 5 columns, separated by ;)
        .ref_id – reference code of the color (NC-001 to NC-020)
        .color_name – name of the shade (e.g. Burgundy, Sage Green)
        .color_family – color group (Red, Pink, Blue, etc.)
        .hex_code – hex value of the color (e.g. #800020)
        .finish – polish finish (Cream, Gloss, Matte, Sheer,Metallic)
Technologies
Pandas
Jupyter Notebook

How to Run
Install the required libraries:

py -m pip install pandas notebook

Open the notebook and run the cells in order:

py -m notebook nail.ipynb

What I Learned
.Loading a CSV file with Pandas (including a custom ; separator)
.Inspecting a dataset with head(), info(), describe() and shape
.Checking for duplicate rows
