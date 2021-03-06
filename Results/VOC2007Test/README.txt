This folder contains results from the attempted reproduction of the results given in Table 1 of "Measuring the Objectness of Image Windows".

The test set is based on the Pascal VOC 2007 data set and contains 7610 images. For each image, the method proposed in "Measuring the Objectness of Image Windows" returns a number of windows that may contain objects. Each window also has a score indicating how confident the method is in ther being an object there.
Each window is given on the format (xmin ymin xmax ymax score).

The results in this folder is as follows:
- Results.csv is a semicolon separated file containing the reproduced detection rate for 10, 100, and 1000 windows for four cue combinations. The values should be compared with those given in Table 1 of "Measuring the Objectness of Image Windows".
- VOC2007Test.csv is a semicolon separated file containing the id and windows for all images. The first column gives the id of the image, and the second column contains a list of all windows identified for that image.
- The 'Images' folder contains a separate semicolon separated file for each image. The name of a file is the id of the image, each row is a window identified for that image, and the columns are (xmin ymin xmax ymax score).