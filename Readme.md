# DentScan: Automated Dental Angle Analysis

## Overview
DentScan is a project developed as part of the "Decision Support Systems" module by Hamza Jakouk under the supervision of Pr.HRIMECH Hamid at Université Hassan 1er. This project aims to address the complexities of modern dental medicine by providing an automated tool for precise dental angle analysis.

## Introduction
The analysis of dental angles is a crucial aspect of dental diagnostics and treatment planning. DentScan, part of the ToothInsight initiative, leverages Data Mining methods applied to a dataset of dental images and XML files containing specific annotations. The project aims to provide dental students with an essential tool for accurate dental analysis.

## Data Augmentation
To improve the resilience and generalization of our model, we implemented data augmentation techniques. This includes creating artificial variations of our image dataset by applying transformations such as rotation, scaling, and translation.

## XML File Processing
The project includes Python functions to extract information from XML files associated with dental images. These functions parse individual XML files, extracting details such as file name, image size, and object coordinates.

## Horizontal and Vertical Flipping
Functions are provided to apply horizontal and vertical flipping transformations to the bounding boxes of objects within an image. These transformations are integrated into the complete dataset, updating the coordinates and saving the transformed images.

## Rotation of Images
The project introduces functions for performing image rotation and adjusting the bounding box coordinates accordingly. The functions use OpenCV to apply affine rotation around the image center and adjust bounding box coordinates based on
the rotation angle.

## Systematic Application of Transformations
A systematic approach is applied to transform the entire dataset. This includes processing the data, applying specified transformations, updating annotations, and saving transformed images in an output directory.

## Results and Discussion
After transformations, the model's results are evaluated to ensure its accuracy and reliability. The project demonstrates significant progress in dental medicine, offering practical applications for improved dental care and advanced professional training.

## Convolutional Neural Network (CNN) Model
DentScan features a CNN model tailored for the task of detecting dental key points in images. The model is trained, evaluated, and tested using the dataset, showing the potential for real-world application in dental medicine.

## Conclusion
The ToothInsight project, through DentScan, has achieved significant advancements in the field of dental medicine. The strategic use of Data Mining techniques on a rich dataset of dental images and annotated XML files has proven to be the cornerstone of our success.

## Acknowledgments
Special thanks to Pr.HRIMECH Hamid for supervising the project and to Université Hassan 1er for providing the resources and support.

