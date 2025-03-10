Back to [Projects List](../../README.md#ProjectsList)

Automatic Quantitative 3D Cephalometrics

## Key Investigators
- Baptiste Baquero (University of Michigan)
- Maxime Gillot (University of Michigan)
- Lucia Cevidanes (University of Michigan)
- David Allemang (Kitware Inc)
- Jean-Christophe Fillion-Robin (Kitware Inc)

# Project Description
AQ3DC is a Slicer extension to automatically do some measurement (angles or distance) between landmarks in different part of the skull. Clinicians will
be able to compute all the measurements at the same time for all their patients. Another application will be to create the middle point between 2
landmarks. 


## Objective

- Objective A. Development of a Slicer extension that will automatically perform angular or linear measurements between landmarks in one or more time points for a all sample of patients.
- Objective B. Generate automatically a "clinical meaning" of the directionality for the numbers and signs obtained after the computation.
- Objective C. Generate the mid point between two landmaks.

## Approach and Plan

1. Work on writing the code in the branch https://github.com/baptistebaquero/Q3DCExtension/tree/add-AQ3DC-module of Q3DC extension, focusing on the steps  described below and with feedback of project team members.


## Progress and Next Steps

# Progress:
1. Pre-selections of the landmarks needed.
2. Import/export excel file with all the measurement needed.
3. Creation of interactive table with the different measurement needed.
4. Computation of linear measurements for one time point and exporting of the data in an excel file.

# Next steps :
1. Compute the linear measurements for different time points.
2. Computation of angular measurements
3. Computation of mid points
4. Implement nodes for interaction with the 3D environment for computations for a single case


# Illustrations

<!-- Add pictures and links to videos that demonstrate what has been accomplished.
![Description of picture](Example2.jpg)
![Some more images](Example2.jpg)
-->
# Goal interface:
![Goal_interface](https://user-images.githubusercontent.com/83285614/174842473-ee02e353-94fe-4b41-ba64-d65cb84c0e7d.png)



# Current interface:
![Current_interface](https://user-images.githubusercontent.com/83285614/174842058-c7d8f30f-82e4-4648-aa76-b81e37a90e99.png)



# Background and References

<!-- If you developed any software, include link to the source code repository. If possible, also add links to sample data, and to any relevant publications. -->
