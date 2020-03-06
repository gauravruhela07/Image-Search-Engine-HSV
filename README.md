# Image Search Engine Using HSV-Values 

This project was aimed at building image search engine using HSV-values extracted from the images. For this image was divided into five sections, and for each section, its HSV values were extracted and stored into a csv file. This csv file was later used to search for images which are similar to the given query image.

## Instructions on How To Use

For extracting HSV values and saving it to index.csv file, run '''python index.py --dataset dataset --index index.csv'''
And now for testing any query images based on the extracted HSV values of the dataset, run '''python search.py --index index.csv --query queries/image.png --result-path dataset'''

## You Must Have Following Libraries Installed
sklearn
matplotlib
opencv


