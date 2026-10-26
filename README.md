# Cosmology Notebooks

**Elisavet Pavlidi**  
Undergraduate Physics student, Astrophysics specialization  
National and Kapodistrian University of Athens, Greece

A collection of computational study notebooks developed while studying cosmology and preparing for my undergraduate thesis on primordial black holes and gravitational wave signatures. Topics follow Daniel Baumann's *Cosmology*, with symbolic calculations, numerical examples and interactive visualizations.

These are educational study materials, not original research publications or a validated simulation package. They include simplifying assumptions and illustrative models. Explanations are in English and Greek.

## Contents and suggested reading order

| Notebook | Topics | Kernel |
| :--- | :--- | :--- |
| [FLRW Cosmology](notebooks/FLRW_Cosmology.ipynb) | FLRW metric, Christoffel symbols, Ricci and Einstein tensors, Friedmann equations, fluids and cosmic expansion | SageMath 10.9 |
| [ΛCDM Visualizations](notebooks/LCDM_Visualizations_append.ipynb) | Cosmic energy densities, density parameters, deceleration and expansion | Python 3 |
| [Inflation Interactive](notebooks/Inflation_Interactive_Baumann_FIXED.ipynb) | Inflationary expansion and interactive illustrations | Python 3 |
| [CMB Anisotropies](notebooks/CMB_Anisotropies.ipynb) | Temperature anisotropies, spherical harmonics and observed Planck 2018 TT bandpowers | Python 3 |
| [Cosmology Interactive Atlas](notebooks/Cosmology_Interactive_Atlas_Baumann.ipynb) | ΛCDM, inflation, perturbations, primordial gravitational waves and CMB | Python 3 |

## Running the Python notebooks

Create an environment and install the dependencies from the repository root:

```bash
python -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
jupyter lab
```

Select the Python 3 kernel for the four Python notebooks and run cells in order. Interactive controls require a running notebook environment; GitHub's static preview does not run sliders or execute cells. Existing outputs remain available where they were saved in the uploaded notebooks.

## Running the SageMath notebook

`FLRW_Cosmology.ipynb` uses SageMath syntax and the SageManifolds tensor tools. It cannot run in a standard Python kernel. Open it in Jupyter with a SageMath kernel; its saved metadata specifies SageMath 10.9. The Python requirements file does not install SageMath.

## Scientific context and sources

* Daniel Baumann, *Cosmology*. The notebooks are accompanying study calculations and visualizations. Chapter and equation references are given within the relevant notebooks.
* Planck 2018 Legacy Release (PR3), [published TT bandpowers hosted by NASA/IPAC IRSA](https://irsa.ipac.caltech.edu/data/Planck/release_3/ancillary-data/cosmoparams/COM_PowerSpect_CMB-TT-binned_R3.01.txt).
* [ESA / Planck Collaboration: Planck's view of the cosmic microwave background](https://www.esa.int/ESA_Multimedia/Images/2018/07/Planck_s_view_of_the_cosmic_microwave_background2).

The CMB notebooks embed TT bandpower tables for offline plotting. The ESA sky image is an external image and requires internet access to display. Observational data, theoretical spectra and schematic visualizations should be interpreted according to the distinctions in each notebook. Third party images and data retain their original credits and usage terms.

## Status

The five notebooks are preserved as uploaded, including their original filenames and saved outputs. Python code cells have been checked for syntax. A complete numerical and scientific review, and execution of the SageMath notebook, have not been performed for this upload.

## Related work

* [GitHub profile](https://github.com/elisavetpavlidi)
* [Primordial Black Hole Formation project](https://github.com/elisavetpavlidi/Primordial-Black-Hole-Formation)

## Reuse

No repository wide reuse license has been selected. Please consult the original sources for third party materials and contact the repository owner about reuse of other content.
