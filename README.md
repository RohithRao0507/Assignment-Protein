# Distance Matrix Calculation Report

## Objective
Calculate the minimal Euclidean distance between the two closest atoms of any two positions in a protein coordinate dataset.

## Dataset Description
The dataset contains X, Y, and Z coordinates for **856** positions of protein atoms.

## Approach
1. **Imported** the dataset from an Excel file.
2. **Created** a function to compute Euclidean distance between two points.
3. **Extracted** unique positions and initialized an empty distance matrix.
4. **For each pair of positions**, computed the pairwise Euclidean distances between their atoms using the defined function.
5. **Recorded** the minimal distance between the positions in the distance matrix.
6. **Saved** the distance matrix as a CSV file.

## Results
The code successfully calculated the minimal Euclidean distance between the closest atoms of any two positions in the protein coordinate dataset. The resulting distance matrix captures these distances in a clear and organized format, providing **valuable insights** into the spatial relationships between protein atoms.

## Conclusion
This code aids in understanding the proximity of atoms across different positions in the protein. The distance matrix serves as a valuable resource for analyzing interatomic distances, aiding in tasks such as **identifying potential binding sites** or investigating structural changes within the protein.
