# Retinal-Defect-Classification-using-CNN-from-OCT-images
Contains code for Deep Learning model for Retinal OCT(optical coherence tomography) Images classiﬁcation which I did for my Machine Learning Project.

<h2> Objective </h2>

Given a new OCT image, determine whether the images belong to which 4 classes: CNV, DRUSEN, DME and NORMAL. We are using CNN for classification model.

<h2> Results </h2>

Accuracy of the model on test data is 96.88%

<h2> Dataset Description </h2>

The dataset is organized into 3 folders (train, test, val) and contains subfolders for each image category (NORMAL,CNV,DME,DRUSEN). There are 84,495 X-Ray images (JPEG) and 4 categories (NORMAL,CNV,DME,DRUSEN).

Images are labeled as (disease)-(randomized patient ID)-(image number by this patient) and split into 4 directories: CNV, DME, DRUSEN, and NORMAL.

Optical coherence tomography (OCT) images (Spectralis OCT, Heidelberg Engineering, Germany) were selected from retrospective cohorts of adult patients from the Shiley Eye Institute of the University of California San Diego, the California Retinal Research Foundation, Medical Center Ophthalmology Associates, the Shanghai First People’s Hospital, and Beijing Tongren Eye Center between July 1, 2013 and March 1, 2017.

<h2> Acknowledgements </h2>

Dataset : https://www.kaggle.com/paultimothymooney/kermany2018 <br>
Citation : http://www.cell.com/cell/fulltext/S0092-8674(18)30154-5
