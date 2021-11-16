# Alexandra Ralevski's Portfolio




## [Project 1: Generating Training Data Using Weak Supervision with Snorkel (NASA)](https://github.com/ARalevski/nasa_petal_snorkel)
- Utilized the [Snorkel system](https://snorkel.ai/) to build a training set of labeled biomimicry papers. 
- Labeling our data by hand was prohibitively slow, so we turned to a weak supervision approach using labeling functions (LFs) in Snorkel.
- LFs are noisy, programmatic rules and heuristics that assign labels to unlabeled training data. 
- We successfully trained a classifier that could predict what label a certain biomimicry paper should receive with 95% accuracy.

<p align="center">
  <img width="1000" src="https://github.com/ARalevski/My_Portfolio/blob/main/images/snorkel_illustration_final_white_blackborder.png"
  <figcaption> An overview of the Snorkel system. (1) Subject matter experts (SME) users write labeling functions (LFs) that express weak supervision sources like distant supervision, patterns, and heuristics. (2) Snorkel applies the LFs over unlabeled data and learns a generative model to combine the LFs' outputs into probabilistic labels. (3) Snorkel uses these labels to train a discriminative classification model, such as a deep neural network. Adapted from Ratner et. al (2017). </a>
  </figcaption>
</p>
  
## [Project 2: Utilizing SciBERT for Binary Classification of Biomimicry Papers (NASA)](https://github.com/ARalevski/nasa_petal_scibert)
- Utilized SciBERT to determine whether a paper would qualify as 'biomimetic' (Y/N).
- Utilized training set of over 10,000 papers.

<!-- <p align="center">
  <img width="500" src="https://github.com/ARalevski/My_Portfolio/blob/main/images/Petal%20Taxonomy%20v2%20June%202021_clipped_new.png"
</p> -->

![](https://github.com/ARalevski/My_Portfolio/blob/main/images/Petal%20Taxonomy%20v2%20June%202021_clipped_new.png)
*The PeTaL taxonomy contains 100 functions, or adaptations, an organism can perform.*


## [Project 3: Employee Retention (Personal Project)](https://github.com/ARalevski/which_employees_leave)
- Generated a machine learning model that predicts which employees are most likely to leave a company.
- Optimized Logistic Regression, Random Forest Regressors, and Boosted Trees using GridsearchCV to determine the best model.
- The winning Random Forest model achieved a 0.99 AUC score and 91% accuracy rate with minimal tuning.

<!-- Solarized dark             |  Solarized Ocean
:-------------------------:|:-------------------------:
![](https://github.com/ARalevski/My_Portfolio/blob/main/images/cf%20matrix%20rf%20model.png", width="425")  |  ![](https://github.com/ARalevski/My_Portfolio/blob/main/images/ROC%20rf.png) -->


<p align="center">
  <img src="https://github.com/ARalevski/My_Portfolio/blob/main/images/cf%20matrix%20rf%20model.png" width="425"/> <img src="https://github.com/ARalevski/My_Portfolio/blob/main/images/ROC%20rf.png" width="374"/>
  </p>
<!-- 
![](https://github.com/ARalevski/My_Portfolio/blob/main/images/cf%20matrix%20rf%20model.png "TITLE") ![](https://github.com/ARalevski/My_Portfolio/blob/main/images/ROC%20rf.png "title-2") -->

<!-- <img src="https://github.com/ARalevski/My_Portfolio/blob/main/images/cf%20matrix%20rf%20model.png" alt="Alert dialog" class="screenshot">
  <figcaption><b>Figure 1</b>: Random Forest Model Confusion Matrix</figcaption> width="425"/> <img src="https://github.com/ARalevski/My_Portfolio/blob/main/images/ROC%20rf.png" width="425"/> -->

<!-- <figure>
  <img src="https://github.com/ARalevski/My_Portfolio/blob/main/images/cf%20matrix%20rf%20model.png"
       alt="Alert dialog" class="screenshot">
  <figcaption><b>Figure 1</b>: Random Forest Model Confusion Matrix</figcaption>
    <img src="https://github.com/ARalevski/My_Portfolio/blob/main/images/ROC%20rf.png"
       alt="Alert dialog" class="screenshot">
  <figcaption><b>Figure 2</b>: ROC Curve for Random Forest Model</figcaption>
</figure>
 -->
<!-- <figure>
  <img src="https://github.com/ARalevski/My_Portfolio/blob/main/images/ROC%20rf.png"
       alt="Alert dialog" class="screenshot">
  <figcaption><b>Figure 1</b>: ROC Curve of Random Forest Model</figcaption>
</figure> -->

### Contact
For questions contact Alexandra Ralevski (alexandra.ralevski@gmail.com)

