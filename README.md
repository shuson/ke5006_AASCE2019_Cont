# Workspace for Accurate Automated Spinal Curvature Estimation Challenge

Class project for KE5006, based on [AASCE 2019](https://aasce19.grand-challenge.org/Home/)

Project Plan and Milestones:
* 20/Jan/2020 -- Draft Project Proposal (This readme)
* 10/Feb/2020 -- Train and Test data study
* 20/Feb/2020 -- Paper reading and review
* 10/Mar/2020 -- Implemetation and evaluation
* 25/Mar/2020 -- Draft Report
* 10/Apr/2020 -- Draft Presentation Slide
* 17/Apr/2020 -- Final report and presentation


### 1. Background
Previously, in KE5108 module, I and my teammates studied and developed a MEAN U-Net based segmentation method to identify the vertebraes and calculate the final cobb angle of the spin. 
In this KE5006 class, I'd like to develop my research skills as well as machine learning coding skills. My initial plan is to solve the problem we face by learning how to find related existing research paper. After all, come out novel idea and implement it to make better result out of it.

### 2. AASCE 2019 Introduction
Accurate automated quantitative estimation of spinal curvature is an important task for the clinical evaluation and treatment planning of Adolescent Idiopathic Scoliosis (AIS). It solves the disadvantage of manual Cobb angle measurement (time-consuming and unreliable) which is the current clinical standard for AIS assessment. A couple of attempts have been made for automated Cobb angle estimation on single-view x-rays. However, it is very challenging to achieve a highly accurate automated estimation of Cobb angles because it is difficult to utilize the information of x-rays efficiently.  [Read more ...](https://aasce19.grand-challenge.org/Home/)

### 3. Data Description & Exploration
HThe training dataset consists of 609 spinal anterior-posterior x-ray images. The landmarks were provided by two professional doctors in London Health Sciences Center. Each vertebra was located by four landmarks with respect to four corners. The Cobb angles were calculated using these landmarks.

Refer to [Data Explanation](https://aasce19.grand-challenge.org/Data/)

