# Interactive Analysis Template

This project provides a template for producing shareable interactive analysis using Python and Jupyter Lab. This can be used for producing dashboard-like reports in which the GOV styling is automatically applied.

## Prerequisites

* [Anaconda Python distribution (latest)](https://www.anaconda.com/products/individual)
* Installation of [HoloViz](https://holoviz.org/) Python packages using:
```
conda install -c conda-forge hvplot
```

## Steps

1. Open interactive_analysis_template.ipynb 

2. Use the template to carry out your analysis

3. To share with others, open export_notebook.ipynb and run export_notebook_to_html() then govify_html() functions. 

4. The HTML output will be generated in the output folder