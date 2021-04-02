Developed two statistical models of colour categorizaton based on Prototype and Exemplar theories of concept categorizaton.

Models trained on Munsell and CIELAB color coordinate data from the World Colour Survey.
The world color survey asks speakers from 110 different languages to label a munsell color palette using color terms (eg. For English: red, dark blue, forest green, etc.) in their language. The speaker data for each language was used to train the model to label a color palette in each language.

This resulted in the prototype and exemplar models to generate 110 munsell palettes each. 

Run or view wcs_cielab.ipynb to see the models' generated color palettes compared to the human generated color palette (which is an average of all the human answers for each leanguage)

Model developed in Python w/ SciPy, scikit-learn, Numpy. Jupyter Notebook

Validated the models using Leave-one-out cross validaton (for each language). Exemplar model was 78% accurate to human data, the prototype model was 72% accurate to human data. 

