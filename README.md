# Cyclic multiplex fluorescent immunohistochemistry and machine learning reveal distinct states of astrocytes and microglia in normal aging and Alzheimer’s disease.

## About

We have developed a methodology of cyclic multiplex fluorescent immunohistochemistry on human postmortem brain sections followed by an image analysis and machine learning pipeline that enables a deep morphological characterization of astrocytes and microglia in the Alzheimer's brain.

## Dependencies

To run our code, please install the following dependencies:

<a href="https://www.r-project.org/" target="_blank" rel="noreferrer noopener"><img src="https://img.shields.io/badge/Language-R-276DC3?style=for-the-badge&amp;logo=r" alt="ayushnoori" align="center"/></a>

<a href="https://imagej.net/" target="_blank" rel="noreferrer noopener"><img src="https://img.shields.io/static/v1?style=for-the-badge&amp;logo=imagej&amp;color=00D8E0&amp;logoColor=white&amp;label=Language&amp;message=ImageJ" alt="ayushnoori" align="center"/></a>

<a href="https://www.python.org/" target="_blank" rel="noreferrer noopener"><img src="https://img.shields.io/badge/Language-Python-3776AB?style=for-the-badge&amp;logo=python" align="center"/></a>

<a href="https://pytorch.org/" target="_blank" rel="noreferrer noopener"><img src="https://img.shields.io/badge/Library-PyTorch-EE4C2C?style=for-the-badge&amp;logo=pytorch" alt="ayushnoori" align="center"/></a>

Additional required libraries are specified in each script. Image segmentation was performed with the FIJI distribution of the open-source Java-based image analysis program ImageJ. Convolutional neural networks (CNN) were constructed using the PyTorch open-source deep learning library in the Python programming language (version 3.8.5). Unless otherwise indicated, all other analyses were performed in the R programming language and statistical computing environment (version 4.1.0).

## Workflow

Please see the analysis workflow below.
<a href="https://www.serranopozolab.org/glia-ihc/#workflow" target="_blank" rel="noreferrer noopener"><img src="https://github.com/serrano-pozo-lab/glia-ihc/blob/main/images/flowchart.svg" width="80%"></a>

## Documentation

To read our documented code, please visit [www.serranopozolab.org/glia-ihc](https://www.serranopozolab.org/glia-ihc).

## Code Availability

Our full codebase is available for download on [GitHub](https://github.com/serrano-pozo-lab/glia-ihc).
