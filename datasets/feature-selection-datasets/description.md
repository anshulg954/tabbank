## 2. `gina_agnostic`
**Description:** Dataset from the Agnostic Learning vs. Prior Knowledge Challenge (http://www.agnostic.inf.ethz.ch), which consisted of 5 different datasets (SYLVA, GINA, NOVA, HIVA, ADA). The purpose of the challenge was to check if the performance of domain-specific feature engineering (prior knowledge) can be met by algorithms that were trained on data without any domain-specific knowledge (agnostic). For the latter, the data was anonymised and preprocessed in a way that makes them uninterpretable.
**Addditional Description:** The task of GINA is handwritten digit recognition. This is the agnostic version of a subset of the MNIST data set. We chose the problem of separating the odd numbers from even numbers. We use 2-digit numbers. Only the unit digit is informative for that task, therefore at least ½ of the features are distracters. This is a twoclass classification problem with sparse continuous input variables, in which each class is composed of several clusters. It is a problems with heterogeneous classes.
- **Source:** <a href="https://www.openml.org/search?type=data&status=active&id=1038&sort=runs">OpenML</a>
- **File:** ![gina_agnostic.csv](../../datasets/feature-selection-datasets/Classification/madelon.csv)
- **#Rows:** 2600  
- **#Features:** 500  
- **Target:** `class (Classification)`  
- **Features:** <br>
`V1 ... V500:` Mixture of informative, redundant and noise features <br>
`(Target) class:` Binary class label (1/2)<br>

## 2. `Madelon Dataset`
- **Description:** Madelon is a synthetic dataset created for the NIPS 2003 Feature Selection Challenge. Samples are arranged in clusters positioned on the vertices of a 5-dimensional hypercube, with only a small subset of features containing true signal. Most features are redundant or pure noise, making it a strong benchmark for feature selection and classification methods.
- **Source:** <a href="https://www.openml.org/d/1485">OpenML</a>
- **File:** ![gina_agnostic.csv](../../datasets/feature-selection-datasets/Classification/gina_agnostic.csv)
- **#Rows:** 3468  
- **#Features:** 971
- **Target:** `label (Classification)`  
- **Note** `Synthetic dataset with 5 informative features, 15 redundant features, and 480 noise features`
- **Features:** <br>
`attr0 ... attr969:` Mixture of informative, redundant and noise features <br>
`(Target) label:` Binary class label (1/-1)<br>

## 3. `Isolet Dataset`
- **Description:** ISOLET (Isolated Letter Speech Recognition) dataset was generated as follows: 150 subjects spoke the name of each letter of the alphabet twice. Hence, there are 52 training examples from each speaker. The speakers are grouped into sets of 30 speakers each, 4 groups can serve as training set, the last group as the test set. A total of 3 examples are missing, the authors dropped them due to difficulties in recording. This is a good domain for a noisy, perceptual task. It is also a very good domain for testing the scaling abilities of algorithms. For example, C4.5 on this domain is slower than backpropagation!
- **Source:** <a href="https://www.openml.org/d/1485">OpenML</a>
- **File:** ![isolet.csv](../../datasets/feature-selection-datasets/Classification/isolet.csv)
- **#Rows:** 7797  
- **#Features:** 618
- **Target:** `class (Classification)`  
**Attribute Information:** All attributes are continuous, real-valued attributes scaled into the range -1.0 to 1.0. The features are described in the paper by Cole and Fanty cited below. The features include spectral coefficients; contour features, sonorant features, pre-sonorant features, and post-sonorant features. The exact order of appearance of the features is not known.
- **Features:** <br>
`f1 ... f617:` Mixture of informative, redundant and noise features <br>
`(Target) class:` class label (26 distinct values)<br>

## 4. `cnae-9 Dataset`
- **Description:**This is a data set containing 1080 documents of free text business descriptions of Brazilian companies categorized into a subset of 9 categories.
- **Source:** <a href="https://www.openml.org/search?type=data&status=active&id=1468&sort=runs">OpenML</a>
- **File:** ![cnae-9.csv](../../datasets/feature-selection-datasets/Classification/cnae-9.csv)
- **#Rows:** 1080
- **#Features:** 857
- **Target:** `class (Classification)`  
**Attribute Information:** In the dataset there are 857 attributes, 1 attributes with the class of instance and 856 with word frequency.
- **Features:** <br>
`V0 ... V856:` Word frequency <br>
`(Target) class:` class label (9 distinct values)<br>

## 5. `har Dataset`
- **Description:** Human Activity Recognition (HAR) database built from the recordings of 30 subjects performing activities of daily living (ADL) while carrying a waist-mounted smartphone with embedded inertial sensors. This dataset version contains all the training and testing examples provided in the original data repository.
The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers were selected for generating the training data and 30% the test data.
The sensor signals (accelerometer and gyroscope) were pre-processed by applying noise filters and then sampled in fixed-width sliding windows of 2.56 sec and 50% overlap (128 readings/window). The sensor acceleration signal, which has gravitational and body motion components, was separated using a Butterworth low-pass filter into body acceleration and gravity. The gravitational force is assumed to have only low-frequency components, therefore a filter with 0.3 Hz cutoff frequency was used. From each window, a vector of features was obtained by calculating variables from the time and frequency domain.
- **Source:** <a href="https://www.openml.org/search?type=data&status=active&id=1478&sort=runs">OpenML</a>
- **File:** ![har.csv](../../datasets/feature-selection-datasets/Classification/har.csv)
- **#Rows:** 10299
- **#Features:** 562
- **Target:** `class (Classification)`  
**Attribute Information:** For each record in the dataset it is provided:
-| Triaxial acceleration from the accelerometer (total acceleration) and the estimated body acceleration.
-| Triaxial Angular velocity from the gyroscope.
-| A 561-feature vector with time and frequency domain variables.
-| It's activity label.
**Features:** <br>
`V0 ... V561:` Time and frequency domain variables <br>
`(Target) class:` class label (6 distinct values)<br>

## 6. `mnist_784 Dataset`
- **Description:** The MNIST database of handwritten digits with 784 features, raw data available at: http://yann.lecun.com/exdb/mnist/. It can be split in a training set of the first 60,000 examples, and a test set of 10,000 examples.
It is a subset of a larger set available from NIST. The digits have been size-normalized and centered in a fixed-size image. It is a good database for people who want to try learning techniques and pattern recognition methods on real-world data while spending minimal efforts on preprocessing and formatting. The original black and white (bilevel) images from NIST were size normalized to fit in a 20x20 pixel box while preserving their aspect ratio. The resulting images contain grey levels as a result of the anti-aliasing technique used by the normalization algorithm. the images were centered in a 28x28 image by computing the center of mass of the pixels, and translating the image so as to position this point at the center of the 28x28 field.
With some classification methods (particularly template-based methods, such as SVM and K-nearest neighbors), the error rate improves when the digits are centered by bounding box rather than center of mass. If you do this kind of pre-processing, you should report it in your publications. The MNIST database was constructed from NIST's NIST originally designated SD-3 as their training set and SD-1 as their test set. However, SD-3 is much cleaner and easier to recognize than SD-1. The reason for this can be found on the fact that SD-3 was collected among Census Bureau employees, while SD-1 was collected among high-school students. Drawing sensible conclusions from learning experiments requires that the result be independent of the choice of training set and test among the complete set of samples. Therefore it was necessary to build a new database by mixing NIST's datasets.
The MNIST training set is composed of 30,000 patterns from SD-3 and 30,000 patterns from SD-1. Our test set was composed of 5,000 patterns from SD-3 and 5,000 patterns from SD-1. The 60,000 pattern training set contained examples from approximately 250 writers. We made sure that the sets of writers of the training set and test set were disjoint. SD-1 contains 58,527 digit images written by 500 different writers. In contrast to SD-3, where blocks of data from each writer appeared in sequence, the data in SD-1 is scrambled. Writer identities for SD-1 is available and we used this information to unscramble the writers. We then split SD-1 in two: characters written by the first 250 writers went into our new training set. The remaining 250 writers were placed in our test set. Thus we had two sets with nearly 30,000 examples each. The new training set was completed with enough examples from SD-3, starting at pattern # 0, to make a full set of 60,000 training patterns. Similarly, the new test set was completed with SD-3 examples starting at pattern # 35,000 to make a full set with 60,000 test patterns. Only a subset of 10,000 test images (5,000 from SD-1 and 5,000 from SD-3) is available on this site. The full 60,000 sample training set is available.
- **Source:** <a href="https://www.openml.org/search?type=data&status=active&id=554&sort=runs">OpenML</a>
- **File:** ![mnist_784.csv](../../datasets/feature-selection-datasets/Classification/mnist_784.csv)
- **#Rows:** 70000
- **#Features:** 785
- **Target:** `class (Classification)`  
**Features:** <br>
`pixel1 ... pixel784:` Pixel values <br>
`(Target) class:` class label (10 distinct values)<br>

## 7. `AP_Colon_Kidney`
- **Description:** GEMLeR provides a collection of gene expression datasets that can be used for benchmarking gene expression oriented machine learning algorithms. They can be used for estimation of different quality metrics (e.g. accuracy, precision, area under ROC curve, etc.) for classification, feature selection or clustering algorithms.
This repository was inspired by an increasing need in machine learning / bioinformatics communities for a collection of microarray classification problems that could be used by different researches. This way many different classification or feature selection techniques can finally be compared to eachother on the same set of problems.
Each gene expression sample in GEMLeR repository comes from a large publicly available expO (Expression Project For Oncology) repository by International Genomics Consortium.
The goal of expO and its consortium supporters is to procure tissue samples under standard conditions and perform gene expression analyses on a clinically annotated set of deidentified tumor samples. The tumor data is updated with clinical outcomes and is released into the public domain without intellectual property restriction. The availability of this information translates into direct benefits for patients, researchers and pharma alike.
- **Source:** <a href="https://www.openml.org/search?type=data&status=active&id=1137">OpenML</a>
- **File:** ![ap_colon_kidney.csv](../../datasets/feature-selection-datasets/Classification/ap_colon_kidney.csv)
- **#Rows:** 546
- **#Features:** 10936
- **Target:** `Tissue (Classification)`  
**Features:** <br>
`ID_REF:` ID of tissue <br>
`All features except ID_REF:` Gene expression <br>
`(Target) tissue:` class label (Kidney / Colon)<br>

## 8.`OVA_Breast`
- **Description:** GEMLeR provides a collection of gene expression datasets that can be used for benchmarking gene expression oriented machine learning algorithms. They can be used for estimation of different quality metrics (e.g. accuracy, precision, area under ROC curve, etc.) for classification, feature selection or clustering algorithms.
This repository was inspired by an increasing need in machine learning / bioinformatics communities for a collection of microarray classification problems that could be used by different researches. This way many different classification or feature selection techniques can finally be compared to eachother on the same set of problems.
Each gene expression sample in GEMLeR repository comes from a large publicly available expO (Expression Project For Oncology) repository by International Genomics Consortium.
The goal of expO and its consortium supporters is to procure tissue samples under standard conditions and perform gene expression analyses on a clinically annotated set of deidentified tumor samples. The tumor data is updated with clinical outcomes and is released into the public domain without intellectual property restriction. The availability of this information translates into direct benefits for patients, researchers and pharma alike.
- **Source:** <a href="https://www.openml.org/search?type=data&status=active&id=1128&sort=runs">OpenML</a>
- **File:** ![ova_breast.csv](../../datasets/feature-selection-datasets/Classification/ova_breast.csv)
- **#Rows:** 1545
- **#Features:** 10936
- **Target:** `Tissue (Classification)`  
**Features:** <br>
`ID_REF:` ID of tissue <br>
`All features except ID_REF:` Gene expression <br>
`(Target) tissue:` class label (Breast / Other)<br>

## 9.`AP_Breast_Kidney`
- **Description:** GEMLeR provides a collection of gene expression datasets that can be used for benchmarking gene expression oriented machine learning algorithms. They can be used for estimation of different quality metrics (e.g. accuracy, precision, area under ROC curve, etc.) for classification, feature selection or clustering algorithms.
This repository was inspired by an increasing need in machine learning / bioinformatics communities for a collection of microarray classification problems that could be used by different researches. This way many different classification or feature selection techniques can finally be compared to eachother on the same set of problems.
Each gene expression sample in GEMLeR repository comes from a large publicly available expO (Expression Project For Oncology) repository by International Genomics Consortium.
The goal of expO and its consortium supporters is to procure tissue samples under standard conditions and perform gene expression analyses on a clinically annotated set of deidentified tumor samples. The tumor data is updated with clinical outcomes and is released into the public domain without intellectual property restriction. The availability of this information translates into direct benefits for patients, researchers and pharma alike.
- **Source:** <a href="https://www.openml.org/search?type=data&status=active&id=1128&sort=runs">OpenML</a>
- **File:** ![ap_breast_kidney.csv](../../datasets/feature-selection-datasets/Classification/ap_breast_kidney.csv)
- **#Rows:** 604
- **#Features:** 10936
- **Target:** `Tissue (Classification)`  
**Features:** <br>
`ID_REF:` ID of tissue <br>
`All features except ID_REF:` Gene expression <br>
`(Target) tissue:` class label (Kidney / Breast)<br>

## 9.`AP_Breast_Ovary`
- **Description:** GEMLeR provides a collection of gene expression datasets that can be used for benchmarking gene expression oriented machine learning algorithms. They can be used for estimation of different quality metrics (e.g. accuracy, precision, area under ROC curve, etc.) for classification, feature selection or clustering algorithms.
This repository was inspired by an increasing need in machine learning / bioinformatics communities for a collection of microarray classification problems that could be used by different researches. This way many different classification or feature selection techniques can finally be compared to eachother on the same set of problems.
Each gene expression sample in GEMLeR repository comes from a large publicly available expO (Expression Project For Oncology) repository by International Genomics Consortium.
The goal of expO and its consortium supporters is to procure tissue samples under standard conditions and perform gene expression analyses on a clinically annotated set of deidentified tumor samples. The tumor data is updated with clinical outcomes and is released into the public domain without intellectual property restriction. The availability of this information translates into direct benefits for patients, researchers and pharma alike.
- **Source:** <a href="https://www.openml.org/search?type=data&status=active&id=1128&sort=runs">OpenML</a>
- **File:** ![ap_breast_ovary.csv](../../datasets/feature-selection-datasets/Classification/ap_breast_ovary.csv)
- **#Rows:** 542
- **#Features:** 10936
- **Target:** `Tissue (Classification)`  
**Features:** <br>
`ID_REF:` ID of tissue <br>
`All features except ID_REF:` Gene expression <br>
`(Target) tissue:` class label (Ovary / Breast)<br>