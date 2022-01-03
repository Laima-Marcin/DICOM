# DICOM
Exploring 2D medical imaging data

In this exercise I am using the Python package pydicom to extract imaging data from a DICOM file.

I am provided with a dataframe that contains bounding box coordinates for masses that have been identified by a radiologist in three separate DICOM images. 
The dataframe gives the starting X & Y coordinates of the bounding box around each mass, and the width and height of the mass. 
These four values allow me to identify the specific rectangular section of each image that contains a suspicious mass.

My job is to extract the imaging data from each DICOM, visualize it, normalize it, and then visualize only the section of the image that contains the suspicious mass. Throughout this process, I am drawing insights about whether or not intensity values are a particularly good characteristic of masses that might help a machine learning algorithm automatically identify them.


