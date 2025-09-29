# Spectral Match Filter Detection Tutorial With Hyperspectral Data

[![test-pr](https://github.com/danforthcenter/plantcv-tutorial-hyperspectral-smf-detection/actions/workflows/ci-tests.yml/badge.svg)](https://github.com/danforthcenter/plantcv-tutorial-hyperspectral-smf-detection/actions/workflows/ci-tests.yml)

Example of using PlantCV tools with a Spectral Match Filter Detection Tool from the GatorSense HSI Toolkit https://github.com/GatorSense/hsi_toolkit_py. In this example we identify spectra for training the SMF detector. Then use the identified spectra for detection on the original image used for training, a new image (with infection), and a new image (without infection; mock infected). You would not run this workflow in parallel as it is. There are steps here that make it easier to develop a workflow but that do not make sense to run in parallel. This notebook would also likely be run in two parts. Part one: Identification of spectra for matching. Part 2: Detection using SMF on one image. Here we're showing detection on three images for demonstration purposes.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/danforthcenter/plantcv-tutorial-hyperspectral-smf-detection/HEAD?labpath=index.ipynb)
<a target="_blank" href="https://colab.research.google.com/github/danforthcenter/plantcv-tutorial-hyperspectral-smf-detection.git">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

## Tutorial tags/keywords

Hyperspectral, Detection, Spectral Match Filter, Disease Detection, Disease Discrimination, Sorghum, Bacterial, Pathogen, GatorSense, Machine Learning, Spectral Signature

## Citations

Alina Zare, Susan Meerdink, Yutai Zhou, Caleb Robey, Ron Fick, John Henning, & Paul Gader. (2019, April 12). GatorSense/hsi_toolkit_py: Initial Release (Version v1.0). Zenodo. http://doi.org/10.5281/zenodo.2638117
