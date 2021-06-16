# Stars Type Prediction

- [Notebook Kaggle](https://www.kaggle.com/d4rklucif3r/stars-type-plotly-luciferml)
- [Dataset Kaggle](https://www.kaggle.com/deepu1109/star-dataset)

## About Dataset

This is a dataset consisting of several features of stars.

Some of them are:

Absolute Temperature (in K)
Relative Luminosity (L/Lo)
Relative Radius (R/Ro)
Absolute Magnitude (Mv)
Star Color (white,Red,Blue,Yellow,yellow-orange etc)
Spectral Class (O,B,A,F,G,K,,M)
Star Type **(Red Dwarf, Brown Dwarf, White Dwarf, Main Sequence , SuperGiants, HyperGiants)**
Lo = 3.828 x 10^26 Watts (Avg Luminosity of Sun)
Ro = 6.9551 x 10^8 m (Avg Radius of Sun)

## Purpose

The purpose of making the dataset is to prove that the stars follows a certain graph in the celestial Space ,
specifically called Hertzsprung-Russell Diagram or simply HR-Diagram
so that we can classify stars by plotting its features based on that graph.

Data Collection and Preparation techniques:
The dataset is created based on several equations in astrophysics. They are given below:

- Stefan-Boltzmann's law of Black body radiation (To find the luminosity of a star)
- Wienn's Displacement law (for finding surface temperature of a star using wavelength)
- Absolute magnitude relation
- Radius of a star using parallax .
- The dataset took 3 weeks to collect for 240 stars which are mostly collected from web.
- The missing data were manually calculated using those equations of astrophysics given above.

## Acknowledgements

Wikipedia
Stars and Galaxies by SEEDS | Backman

## Repo Link

[AstroML](https://github.com/deepraj1729/AstroML)
