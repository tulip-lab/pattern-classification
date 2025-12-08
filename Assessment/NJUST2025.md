[![GitHub watchers](https://img.shields.io/badge/tulip--lab-Pattern--Classification-brightgreen)](../README.md)
[![GitHub watchers](https://img.shields.io/badge/Module-Induction-orange)](../S00-Induction/README.md)



# :sunny: Unit Assessment

:point_right: This version of this document is for **NJUST-PR2025**.
- Your university might have different setting for assessment. Please contact your [coordinator](../S00-Induction/S00B-Team.md#contacts).


## Task :one: - Advanced Topic Presentation (55%)

All groups are required to give one 25-minute presentation (PPT with Voice Annotation) in this unit. The presentation should be on one of the following specified topics.

The group is required to prepare a presentation together with practical materials and code demonstration, for **any** of the following topics. Please note that most of the following listed topics are beyond the content covered in the lectures:


- T01: **Markov Chain Monte Carlo** (MCMC) Method 
  - Monte Carlo methods are computational techniques that make use of random numbers. The aims of Monte Carlo methods are to generate samples from a given probability distribution, or to estimate the expectations of functions under this distribution. MCMC is the Monte Carlo methods based on Markov Chain, and currently the state-of-the-art methods is the NUTS method:
    - M. D. Hoffman, A. Gelman, [The No-U-Turn Sampler: Adaptively Setting Path Lengths in Hamiltonian Monte Carlo](http://arxiv.org/abs/1111.4246) (2011). 
    - You can refer to the demo at: https://chi-feng.github.io/mcmc-demo/.

- T02: **Gaussian Process**
  - Gaussian process is the joint distribution of all those random variables, and as such, it is a distribution over functions with a continuous domain, e.g. time or space. A machine-learning algorithm that involves a Gaussian process uses lazy learning and a measure of the similarity between points to predict the value for an unseen point from training data.


- T03: **Bayesian Optimization** 
  - Bayesian optimization is a sequential design strategy for global optimization of black-box functions that does not assume any functional forms. It is usually employed to optimize expensive-to-evaluate functions, understanding this will benefit the training of large scale neural networks.


- T04: **No Free Lunch** Theorem 
  - It is impossible to find a classifier which is superior to all other classifiers. Under what kind of scenario, we can construct a classifier using the given data set? Refer to Chapter 9 of the textbook.


- T06: **Chinese Restaurant Problem and Indian Buffet Problem** 
  - The `Chinese Restaurant Problem` (CRP) and the `Indian Buffet Problem` (IBP) are both probabilistic models used to describe clustering or grouping phenomena. 
  - The CRP assigns customers to tables, while the IBP assigns customers to dishes. 
  - These models provide different perspectives on the process of assigning objects to clusters and have found applications in various areas, including machine learning, natural language processing, and social network analysis.


### :mailbox_with_mail: Task :one: Submission

#### Presentation Files Submission

Students are required to submit the Presentation files together with their group details to [unit chair](../S00-Induction/S00B-Team.md#contacts). The unit chair will reply with an acknowledgement email upon the successful arrival of your file. If you didn't receive any acknowledgement, it means that the submission was not received.

Refer to [Assessment Submission Guidelines](../S00-Induction/S00D-Assessment.md#guidelines) on how to submit. 

This assignment submission package should include the following components:

- **Slides**: Slides a PPTX file of your presentation.
- **Practicals**: Practical materials in the format of Jupyter Notebook, similar to the HMM notebook on GitHub repository FLIP01.
- **ScreenCast** or **Voice Annotated Presentation** (Optional): You can include a screen-cast video to capture your presentation together with practicals demo. This  is optional if your group has presented in class.
- **Readings**: A collection of no more than 5 readings relevant for this topic.


### :triangular_ruler: Task :one: Rubrics

Task :one: will be marked by the following criteria:

- 30% will be based on the content and organization of the presentation
- 20% will be based on the quality (novelty, accuracy or performance) of the reported project results;
- 10%
will be based on the clarity of the slides:
    - the readability of the slides using the 7 × 7 rule (7 words per line and 7 lines per slide as a rough guide i.e. slides not too cramped with info.) including correct English;
    - consistency of style (e.g. no more than 2 fonts on each slide and same colours/backgrounds used throughout - generally) and
    - consistency of animation/transitions - not too much as it is a distraction;
    - Use of text colour to highlight important words/phrases for the viewer;
- 10% will be based on Speaking Coherence/Quality, and it will assess whether the speech flows well:
    - No or not many *umms* and *ahs*, stutters, false starts or tripping over words.
    - The voice would be not a complete monotone - use of inflection and emphasis with the voice - and easy to understand - taking accents and English as a second language into consideration.
- 10% will be based on quality of visual aids: some demonstration of software, website, or whatever suitable to support the claim in presentation.
- 10% will be based on timing: full marks for a presentation that fits into the 15-20 minutes ±10% (90 secs). Marks are lost proportionally to the shortness or length outside the range. e.g. a presentation of 13 minutes would be 75 − 80% range likewise 22 minutes.
- 10% will be based on ability to deal with questions: this item is applicable for On campus students only.

Marks will also be allocated for quality audience questions.


## Task :two: - Project (45%)


### 1. Background

Modern gas companies increasingly rely on IoT monitoring systems installed across pipelines, storage tanks, and distribution networks. These sensors collect continuous data such as pressure, temperature, flow rate, vibration, and gas composition. Such data streams create opportunities to apply Pattern Classification and AI methods to improve operational safety, detect anomalies, and optimize performance.

The goal of this assignment is for you to design a **real-world pattern recognition or general AI solution** for a scenario in the gas industry. You will define the problem, consider what data can be collected, and propose how classification methods from this unit (and beyond) can be applied to solve it.

This task is designed to:
- Help you gain **hands-on experience** developing solutions for real projects.
- Strengthen your **academic writing skills** through a structured, well-reasoned report.

Implementation is optional, but your report must demonstrate clear understanding, thoughtful design, and practical considerations for applying Pattern Recognition in an IoT-driven environment.


### 2. Task Description and Objectives

In this assignment, you will design a **Pattern Classification or general AI solution** for a real-world scenario in the gas industry, using IoT sensor data as the foundation. Your task is to select a realistic application scenario, define the classification problem, and propose how methods introduced in this unit (and any additional methods you find appropriate) can be applied to solve it.

You may choose from typical gas-company IoT applications—such as gas leak detection, pipeline condition monitoring, equipment fault classification, gas quality identification, or customer usage pattern analysis—or propose your own scenario with justification.

#### What You Are Expected to Do
- **Define the problem clearly:** Describe the business context, the classification objective, and the expected system outputs.
- **Explain the data:** Identify what IoT devices and signals would be used, how data would be collected, and what preprocessing or feature extraction is required.
- **Design a classification solution:** Choose suitable Pattern Recognition or AI methods, justify your choices, and outline how the model would operate.
- **Describe how performance will be evaluated:** Select appropriate metrics and validation strategies, and explain why they are suitable for your scenario.
- **Discuss deployment considerations:** Reflect on practical issues such as real-time constraints, sensor reliability, edge vs. cloud inference, model updating, and integration into existing systems.

#### Objectives of This Task
This assignment aims to help you:

1. Gain **hands-on experience** in conceptualizing and designing a real-world Pattern Recognition or AI solution.  
2. Develop the ability to **translate domain problems into classification tasks**, including data design, feature extraction, and model selection.  
3. Strengthen your **academic writing skills**, producing a clear and structured technical report that explains your reasoning and design decisions.  
4. Demonstrate understanding of how **Pattern Classification methods**—and their evaluation—apply in an IoT-driven industrial environment.

Implementation or coding is optional; the primary focus is on **analytical design, justification, and clear communication** through your report.

### 3. Expected Report Structure

Your report should follow a clear and professional academic format. The structure below outlines the required sections and provides concise examples to help guide your writing. While coding is optional, your report must demonstrate sound reasoning, appropriate use of pattern classification concepts, and thoughtful consideration of real-world deployment issues.

---

#### 3.1 Cover Page
Include:
- Project title  
- Student name and ID  
- Unit code  
- Date of submission  

---

#### 3.2 Executive Summary (150–250 words)
Provide a concise overview of the problem, proposed solution, and key contributions.

**Example:**  
*This project proposes a classification-based framework for detecting abnormal pipeline conditions using IoT pressure and acoustic sensors. We outline a feature engineering pipeline based on time- and frequency-domain descriptors and propose an SVM classifier to distinguish normal, early-leak, and severe-leak conditions. Evaluation metrics such as recall and F1-score are selected due to the safety-critical nature of leak detection. Deployment issues such as real-time constraints, sensor noise, and edge-based processing are discussed.*

---

#### 3.3 Problem Definition
Describe the application scenario and the classification objective.

Include:
- Business context  
- What classes will be predicted  
- Why classification is relevant  

**Example:**  
*The goal is to classify pipeline health into three categories: Normal, Early-Leak, and Severe-Leak, based on multivariate IoT sensor readings.*

---

#### 3.4 IoT Sensor and Data Design
Explain what data the system will use and how it will be acquired.

Include:
- Sensor types (e.g., pressure, flow, vibration, acoustic, gas composition)  
- Data characteristics (sampling rate, dimensionality)  
- Preprocessing (filtering, segmentation, normalization)

**Example:**  
*Acoustic sensors sampled at 5 kHz are processed into 1-second windows, normalized, and transformed using FFT to extract dominant frequency peaks.*

---

#### 3.5 Feature Engineering
Describe the features used to represent the data.

Options include:
- Statistical time-domain features  
- Frequency-domain features (FFT, wavelets)  
- Dimensionality reduction (PCA, LDA)

**Example:**  
*The feature vector includes variance, spectral centroid, and 20 FFT coefficients.*

---

#### 3.6 Classification Model Design
Explain and justify the classifier(s) you choose.

Discuss:
- Selected model(s) (e.g., k-NN, SVM, Naïve Bayes, Random Forest, ANN)  
- Why the method is appropriate  
- Expected decision boundary characteristics  
- Any assumptions made

**Example:**  
*An RBF-SVM is selected due to expected non-linear separation between leak severity classes.*

---

#### 3.7 Evaluation Strategy
Describe how you will measure performance.

Include:
- Metrics (accuracy, recall, precision, F1-score, ROC-AUC)  
- Validation methods (train/test split, cross-validation)  
- Consideration of class imbalance  
- Cost-sensitive evaluation if applicable

**Example:**  
*Recall for Early-Leak and Severe-Leak is prioritized because missing these conditions can cause significant operational risk.*

---

#### 3.8 Deployment Considerations
Discuss practical challenges and requirements for real-world deployment.

Consider:
- Edge vs. cloud processing  
- Latency and real-time constraints  
- Sensor reliability and noise  
- Model updating and drift  
- Integration with gas company monitoring systems  

**Example:**  
*Inference must run on an edge device every 0.5 seconds, with periodic retraining performed on cloud servers.*

---

#### 3.9 Conclusion
Summarize your proposed solution, key insights, and potential future improvements.

---

#### 3.10 References
List all sources cited in your report in an appropriate academic format.

### :mailbox_with_mail: Task :two: Submission


This task submission package should include the following components:

- **Report**: A single, well-structured `PDF` file of your project report that includes all sections outlined above. 

The report should demonstrate:
- Clear problem definition  
- Appropriate IoT data and feature design  
- A justified classification method  
- A sound evaluation plan  
- Realistic deployment considerations  
- Professional academic writing  

- Optional components may contribute to a stronger impression but are *not required* to receive full marks.



### :triangular_ruler: Task :two: Rubrics

The performance of your practise in this project will decide your mark for this component. It is important to develop your best possible method for your chosen project. The project will be assessed based on it performance, as well as the novelty of your proposed/designed methods, and the clarity of your report, which should make up almost entirely of your own writing.

Task :two: will be evaluated according to the following expectations:

- Content It is expected to see
  - centers on issues or a problem (not just *facts* or summaries);
  - analyzes and explains significance;
  - *develops* (does not merely *collect*) information; 
  - *comments* and *interprets*;
  - current — may include historical sources but acknowledges the most recent research about the issue;
  - answers who-what-where-why-when-with what results-so what?
  - software tools if possible, or a reference to existing research source code
resources.
- Readers Awareness defines the area and its related issues in terms of the readers' needs,
interests, and viewpoints
- Organization Well organized report usually have
  - organized by topics or issues rather than by sources (consider a classification/- partition pattern);
  - begins with a problem and ends with methods, results or significance
  - headings may reveal the main divisions by indicating subtopics
- Style a good style means
  - using lots of concrete words, good action verbs;
  - the author's own voice dominates (not a string of quotes);

Final marks also depend on the quality and creativity of your writing, analysis and description of the related work.
