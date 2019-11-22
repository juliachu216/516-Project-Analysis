## What is Chronic Wasting Disease?
Chronic Wasting Disease (CWD) is a contagious neurological disease affecting deer, elk and moose. It causes a characteristic spongy degeneration of the brains of infected animals resulting in emaciation, abnormal behavior, loss of bodily functions and death.

CWD belongs to a group of diseases known as transmissible spongiform encephalopathies (TSEs). Within this family of diseases, there are several other variants that affect domestic animals: scrapie, which has been identified in domestic sheep and goats for more than 200 years, bovine spongiform encephalopathy (BSE) in cattle (also known as “mad cow disease”), and transmissible mink encephalopathy in farmed mink.

Several rare human diseases are also TSEs. Creutzfeldt-Jakob disease (CJD) occurs naturally in about one out of every one million people worldwide. Variant Creutzfeldt-Jakob disease (v-CJD) has been associated with the large-scale outbreak of BSE in cattle herds in Great Britain.

## Why are we concerned about Chronic Wasting Disease?
CWD poses serious problems for wildlife managers, and the implications for free-ranging deer and elk are significant:

* Ongoing surveillance programs are expensive and draw resources from other wildlife management needs.
* Impacts of CWD on population dynamics of deer and elk are presently unknown. Computer modeling suggests that CWD could substantially reduce infected cervid populations by lowering adult survival rates and destabilizing long-term population dynamics.
* Where it occurs, CWD may alter the management of wild deer and elk populations, and it has already begun to do so.
* Ultimately, public and agency concerns and perceptions about human health risks associated with all TSE’s may erode hunters confidence and their willingness to hunt in areas where CWD occurs.

## How do we study Chronic Wasting Disease in this project?
We propose to evaluate the effectiveness of Raman spectroscopy on skin biopsies from white-tailed deer infected with CWD. We collected two sets of Raman spectrum data, oringinal samples and deparaffined samples, to compare the accuracy after machine learning.  

### Samples preparation

#### Set 1 - Oringnal Samples
All of skin samples are from tail head. They are fixed in formaldehyde, then rinsed with ethanol and embedded in paraffin. After embedding, they are put on gold slides to prepare detection.

#### Set 2 - Deparaffined Samples
Deparaffin skin samples in set 1. 
To deparaffinize the slides, they have to undergo incubation in xylene followed by a descending alcohol series as follows: 
1. 10min incubation in Xylene
2. 10min incubation in 100% ethanol
3. 10min incubation in 95% ethanol
4. 10min incubation in 70% ethanol
5. 10min incubation in DI water. 

### Raman spectrum collection 
Device: DXR Raman Microscope 
Set 1: 
* 20 sec exposure time with 2 sample exposures
* 10x 0.25 BD microscope objective
Set 2: 
* 20 sec exposure time with 5 sample exposures
* 10x 0.25 BD microscope objective

### Raman spectrum Data Analyze

#### Pre-processing
1. Combine negative and positive data separately

  Columns are wavelength value. Rows are different samples.
2. Smooth by moving average method

  Define a smooth function
3. Baseline Correction by polynomial fitting method

  Define a baseline correction function


The final data frame is 520 rows × 1557 columns. The first 280 rows are negative signed as N, and the rest are positive signed as P.

#### Classification
1. Principal Component Analysis

  Reduce the variable to 10 components.

2. Support Vector Machine

  Use GridSearchCV to find the best parameters in suport vector machine.

3. Neural Network

  Create a neural network model with 9 hidden layers, and the output layer is 2 classes (binary classification, 0 or 1). 

### Communciate and visualize the results

What did you learn and do the results make sense?  Revisit your initial question and answer it. 



