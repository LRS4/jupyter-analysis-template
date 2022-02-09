# Interactive Analysis Template

This project provides a template for producing shareable interactive analysis using Python and Jupyter Lab. This can be used for producing dashboard-like reports in which the GOV styling is automatically applied.

## Prerequisites

* Anaconda Python distribution (latest)
* Installation of HoloViz hvplot using:
```
conda install -c conda-forge hvplot
```

## Steps

1. Open interactive_analysis_template.ipynb 

2. Use the template to carry out your analysis

3. To share with others, open export_notebook.ipynb and run the export_notebook_to_govified_html function

4. The HTML output will be generated in the output folder 

## Libraries

The Anaconda Python distribution was used in the template example. The main libraries used were:

* Numpy, Pandas
* Matplotlib, Seaborn
* HoloViews, Bokeh