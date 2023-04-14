# Useful_Scripts

In this repository there are some miscellaneous functions for doing helpful things with your datasets:

Filter: This code takes a pickle import folder which has the properties mol_id, shift and type_int (atomic number) and scans through the dataset and reports any errors present in the molecules

Molecule visuliser: Input your test files after prediction and this will print out a picture of the molecule with the worst prediction with the specific atom which is poorly predicted highlighted, and below will be the error in the prediction

Post IMPRESSION reader: This can be used after IMPRESSION prediction to generate a PNG file of your molecule with atoms labelled, and csv files of the predicted shifts split by atom number, the J couplings are also given
