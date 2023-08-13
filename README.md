# Part 1: Distance Matrix Calculation Report

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

<hr>

# Part 2: Distance Matrix Calculation Report

## Objective
Estimate the 2F5 outcome (restraint or sensitive) for viruses based on the sequence, and identify the positions with the highest association level with the outcome

## Dataset Description
The dataset contains the Env sequence for 796 viruses from patients (856 characters long each from columns C through AFZ. Column B describes the outcome – whether the virus is resistant (1) or sensitive (0) to the therapeutic 2F5 while column A describes the name of the virus. 

## Approach
1. **Imported** the dataset from an Excel file.
2. **Cleared** the data from all the noise.
3. **Converted** categorical columns to numerical using Label Encoding.
4. **Split** data into 80:20 ratio for training and testing. 
5. **At last**, tried to find the importance along with the position and saved the data in descending order in a CSV file.
6. **Finally** drawn a graph showing the importance of each one. 

## Results
The code is successful in identifying the new virus with 96% accuracy and in the Excel output it placed the highest association level in descending order. 

## Conclusion
This code aids in recognizing if a new virus is resistant or sensitive with therapeutic 2F5. and it finds the positions along with their association level to outcome. 
