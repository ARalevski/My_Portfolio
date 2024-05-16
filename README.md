# Alexandra Ralevski's Portfolio


## [Project 1: Using LLMs to Annotate Complex Unstructured Clinical Data](https://github.com/Hadlock-Lab/LLM_SDoH)
- Led a Generative AI team in collaboration with Providence Health to use Large Language Models to extract complex unstructured data from 25,217 notes from 795 pregnant patients.
- Used Chain-of-Thought prompting and few-shot learning to extract SDoH (Social Determinants of Health) data with higher recall than human annotators (0.92) and a precision of 0.85.
- This work demonstrates that LLMs, when compared with manual annotation, provide a scalable, cost-effective solution with the advantage of greater recall.
- More efficient methods for obtaining structured SDoH data can help accelerate inclusion of exposome variables in biomedical research, and support healthcare systems in identifying patients who could benefit from proactive outreach.

<p align="center">
  <img width="1000" src="https://github.com/ARalevski/My_Portfolio/blob/main/images/Fig1_grouped_excel_no_table.png"
  <figcaption> Comparison of recall and precision for Regex, GPT-3.5, GPT-4, and manual annotation in identifying notes with current or past housing instability, measured on 539 manually annotated notes. </a>
  </figcaption>
</p>

## [Project 2: AI-Based Risk Prediction of CKD Patients](https://github.com/Hadlock-Lab/T2D_CKD_risk_model/tree/main)
- Developed an XGBoost model with an AUROC of 0.83 to identify patients at high risk of CKD (Chronic Kidney Disease).
- Developed CROP (Clinical Recruitment Optimization Pipeline), a statistical method that improves ML predictions to identify high-risk patients for clinical trials.
- Use of CROP & CKD risk model resulted in a six-fold decrease in the total number of patients needed for clinical trial recruitment.

<p align="center">
  <img width="1000" src="https://github.com/ARalevski/My_Portfolio/blob/main/images/CROP_overview.png"
  <figcaption> An overview of the Snorkel system. (1) Subject matter experts (SME) users write labeling functions (LFs) that express weak supervision sources like distant supervision, patterns, and heuristics. (2) Snorkel applies the LFs over unlabeled data and learns a generative model to combine the LFs' outputs into probabilistic labels. (3) Snorkel uses these labels to train a discriminative classification model, such as a deep neural network. Adapted from Ratner et. al (2017). </a>
  </figcaption>
</p>

## [Project 3: Generating Training Data Using Weak Supervision with Snorkel (NASA)](https://github.com/ARalevski/nasa_petal_snorkel)
- Utilized the [Snorkel system](https://snorkel.ai/) to build a training set of labeled biomimicry papers. 
- Labeling our data by hand was prohibitively slow, so we turned to a weak supervision approach using labeling functions (LFs) in Snorkel.
- LFs are noisy, programmatic rules and heuristics that assign labels to unlabeled training data. 
- We successfully trained a classifier that could predict what label a certain biomimicry paper should receive with 95% accuracy.

<p align="center">
  <img width="1000" src="https://github.com/ARalevski/My_Portfolio/blob/main/images/snorkel_illustration_final_white_blackborder.png"
  <figcaption> An overview of the Snorkel system. (1) Subject matter experts (SME) users write labeling functions (LFs) that express weak supervision sources like distant supervision, patterns, and heuristics. (2) Snorkel applies the LFs over unlabeled data and learns a generative model to combine the LFs' outputs into probabilistic labels. (3) Snorkel uses these labels to train a discriminative classification model, such as a deep neural network. Adapted from Ratner et. al (2017). </a>
  </figcaption>
</p>
  
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

