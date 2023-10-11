[![GitHub watchers](https://img.shields.io/badge/tulip--lab-Pattern--Classification-brightgreen)](../README.md)
[![GitHub watchers](https://img.shields.io/badge/Module-Induction-orange)](README.md)

# :sunny: Unit Assessment

The modular structure ties in closely to the unit assessment:

- In order to achieve a `Pass` in this unit, all [core sessions](M00C-Logistics.md#core-sessions) must be satisfactorily completed.
- If you would like to achieve a higher grade than a `Pass`, (e.g. a `Credit`, `Distinction` or `High Distinction`) you will need to complete some [advanced sessions](M00C-Logistics.md#advanced-sessions), as well as some higher level study in the extra readings in the core and advanced modules.

### :secret: Assessment Specification

There will be no examination for this unit, and the final assessment will be mainly based on your group's presentations and your project work. We provide a set of options for the presentations and projects, and you are free to choose any option.

The assessment of the unit primarily focuses on assessing students' attainment of the [unit learning outcomes](S00C-Logistics.md#dart-unit-learning-outcomes)  and their proficiency in applying the covered algorithms/models and theories. 

The tasks below are to be completed in a group of up to 2 or 3 members (confirm this with the unit chair, in every offering). Students are required to familiarize themselves with regulations regarding plagiarism. Information regarding Plagiarism and How to Reference can be found in many universities' website.

#### Task :one: - Advanced Topic Presentation (25%)

All groups are required to give one 25-minute presentation in this unit. The presentation should be on one specified pattern recognition topic.

The group is required to prepare a presentation together with practical materials and video demonstration, for any of the following topics. Please note that most of the following listed topics are beyond the content covered in the lectures:

- T00: **Variational Inference** 
  - Variational Inference (VI) is the accurate method for statistical inference. In its mathematical form, VI is similar to EM algorithm, but they serve different purpose. A good reference can be found at:
    - Michael I. Jordan, Zoubin Ghahramani, Tommi S. Jaakkola & Lawrence K. Saul. [An Introduction to Variational Methods for Graphical Models](https://link.springer.com/content/pdf/10.1023%2FA%3A1007665907178.pdf), Machine Learning volume 37, pages183–233 (1999) 

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

- T05: **Component Analysis** 
  - As the extension to principle analysis, there are many other component analysis methods, such as independent component analysis (ICA), Refer to Chapter 10 of the textbook.

##### :mailbox_with_mail: Task :one: Submission

We will schedule the [presentation session](../README.md#session-plan) close to the end of this year's course delivery. Your group will be required to give an in-class presentation. The teaching team will provide feedback and comments so that the group can improve the work accordingly.

Students are required to submit the Presentation files together with their group details to [unit chair](S00B-Team.md#contacts). The unit chair will reply with an acknowledgement email upon the successful arrival of your file. If you didn’t receive any acknowledgement, it means that the submission was not received.

- The suggested email subject should be something like: `[PR] Presentation TXX (Group XXX)`. 
- For large files, you can upload files to any cloud drive such as `Dropbox`, `OneDrive`, `QQ Drive`, `Baidu Pan` etc., and send me the access URL and password in your submission email.

This assignment submission package should include the following components:

- **Slides**: Slides A PPTX file of your presentation.
- **Practicals**: Practical materials in the format of Jupyter Notebook, similar to the HMM notebook on GitHub repository FLIP01.
- **ScreenCast** or **Voice Annotated Presentation** (Optional): You can include a screen cast video to capture your presentation together with practicals demo. This  is optional if your group has presented in class.
- **Readings**: A collection of no more than 5 readings relevant for this topic.


##### :triangular_ruler: Task :one: Rubrics

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

##### :spiral_calendar: Assessment Due Dates

It is expected that you will submit each assessment task on time. You will not be allowed to submit everything at the last moment, because we will provide you with feedback that you will be expected to use in future assessments.

If you find that you are having trouble meeting your deadlines, speak to the [Unit Chair](S00B-Team.md). 


#### Task :two: - Project (25% + 50%)

The purpose of this task is to help solve a real-world *pattern recognition* or general AI project using (but not limited to) the methods introduced in this unit. This assignment is designed to:
- help you gain hands-on experience in solving real projects;
- help you get experience in  academic writing.

In this assignment, you are required to:

1. Implement the project as required;
2. Develop a report on your method (with adequate justification), your discovery, empirical evaluation and analysis.
3. Deliver a 25 minutes progress presentation on your project (25 marks).


You are free to choose any project from the recommended lists as in this site: 

- [TULIP Open-Projects](https://github.com/tulip-lab/open-projects)

:warning: You can also propose your own projects, subject to unit chair's approval. You may be asked to give a formal presentation on your self proposed project in one of the student presentation sessions. 

##### :mailbox_with_mail: Task :two: Submission

We will schedule the [presentation startup session](../README.md#session-plan) in the middle of the course delivery. Your group will be required to give an in-class presentation. The teaching team will provide feedback and comments so that the group can improve the work accordingly.

Students are required to submit the Presentation files together with their group details to [unit chair](S00B-Team.md#contacts). The unit chair will reply with an acknowledgement email upon the successful arrival of your file. 

If you didn't receive any acknowledgement, it means that the submission was not received.

- The suggested email subject should be something like: `[PR] Project Work (Group XXX)`. 
- For large files, you can upload files to any cloud drive such as `Dropbox`, `OneDrive`, `QQ Drive`, `Baidu Pan` etc., and send me the access URL and password in your submission email.

This task submission package should include the following components:

- **Source Code** with proper comments: The implementation of your project. If the project also requires a testing data set, please submit the predicted testing file in this part.
- **Slides**: A `PPTX` file of your project presentation.
- **Report**: A `PDF` file of your project report. Pay attention to the method justification, and model evaluation, most previous students lost marks in those parts.
- **ScreenCast** or **Voice Annotated Presentation** (Optional): You can include a screen cast video to illustrate the running of your project and capture your presentation. This part is *compulsory*. 


##### :triangular_ruler: Task :two: Rubrics

The performance of your practise in this project will decide your mark for this component. It is important to develop your best possible method for your chosen project. The project will be assessed based on it performance, as well as the novelty of your proposed/designed methods, and the clarity of your report, which should make up almost entirely of your own writing.

Task :two: will be evaluated according to the following expectations:

- Content It is expected to see
  - centers on issues or a problem (not just “facts” or summaries);
  - analyzes and explains significance;
  - *develops* (does not merely *collect*) information; 
  - *comments* and *interprets*;
  - current — may include historical sources but acknowledges the most recent research about the issue;
  - answers who-what-where-why-when-with what results-so what?
  - software tools if possible, or a reference to existing research source code
resources.
- Readers Awareness defines the area and its related issues in terms of the readers’ needs,
interests, and viewpoints
- Organization Well organized report usually have
  - organized by topics or issues rather than by sources (consider a classification/- partition pattern);
  - begins with a “problem” and ends with methods, results or significance
  - headings may reveal the main divisions by indicating subtopics
- Style a good style means
  - using lots of concrete words, good action verbs;
  - the author’s own voice dominates (not a string of quotes);

Final marks also depend on the quality and creativity of your writing, analysis and description of the related work.




#### :u6e80: Grades

The final grade (or mark) you receive has a real meaning. A `Pass` reflects that *you have satisfactorily mastered all required learning*, while a higher grade indicates that *you've achieved above and beyond this basic understanding*. Typically, your final grade/mark reflects how much you have achieved in those sessions: 

- `Pass`: Complete all [core sessions](S00C-Logistics.md#core-sessions).
- `Credit`: Complete all [core sessions](S00C-sessions.md#core-sessions), plus one [advanced sessions](S00C-Logistics.md#advanced-sessions) or extra reading.
- `Distinction`: Complete all [core sessions](S00C-Logistics.md#core-sessions), plus the assessment task which is related to [advanced sessions](S00C-Logistics.md#advanced-sessions) or extra reading (this includes the ones you would complete for a `Credit`), with **satisfactory** performance.
- `High Distinction`: Complete all [core sessions](S00C-Logistics.md#core-sessions), plus the assessment task which is related to [advanced sessions](S00C-Logistics.md#advanced-sessions) or extra reading, with **outstanding** performance.  You may define and research an additional topic (that is, fulfil all the criteria for a `distinction`), and the teaching team will assist you in validating an appropriate topic for study.


You must also write a report and present (virtual presentations) on a more advanced topic (which can be the one you studied from the `Distinction`). The teaching team will provide guidance on how to do this. 

###  :scream_cat: Getting Help

As mentioned above, we can provide you with a greater level of support, particularly if you're feeling stuck. Our aim is for that support to be there at the time you need it. It's quite normal to meet some difficulties from time to time. If you already knew how to do everything, there wouldn't be much learning happening, would there? If you are having troubles going through some content, here are some of the things that you can do:

#### :koko: Have issues with assumed knowledge?

-  Ask it under the relevant topic in the discussion forums (check the previous discussions first: your question might already have been answered)
- If you need class time and tutor support, you are welcome to attend any session. 
    - You are encouraged to discuss this with the unit chair, who will give you suitable recommendations.


#### :koko: Have a question?

- Discussion forums – within the `Discussions` area of [`CloudDeakin`](https://d2l.deakin.edu.au) `SIT742` unit site, you will see a forum for you to post questions for each module, preliminary, core and advanced. You don't have to wait to be in class, or for the next help hub session to ask your question, and you are likely to get a prompt answer by other students or the teaching staff. You might find that your questions have already been asked and answered, and if not, your question is likely to help others who struggle with the same issues.

#### :koko: Need a study-mate, for group work, motivation or to bounce ideas?

- The assessment task might be a group work. In case that a group is needed, you can either post messages in the discussion, or form a group with peers when attending the class or practicals.
#### :koko: Have a more personal issue affecting your studies?

- [teaching team](S00B-Team.md#unit-team-contacts) – you can reach out to the teaching team directly by email, particularly in case of more personal problems.
- Email the unit chair.


## Activities

Across the semester (the period of this unit delivery), we will have several sessions for student presentation or other feedback.  
### Activity 0

![GitHub watchers](https://img.shields.io/badge/PR-Learning--Activity-yellow)
> 0. Access this year's assessment tasks, and compare it with those demonstration tasks covered in practical classes. Make a study plan for your `Pattern Classification` study, and think about forming a team for group assessment. 


### Activity 1

![GitHub watchers](https://img.shields.io/badge/PR-Learning--Activity-yellow)
> 1. Access this year's assessment tasks, and compare it with those demonstration tasks covered in practical classes. Make a study plan for your `Pattern Classification` study, and think about forming a team for group assessment. 


### Activity 2

![GitHub watchers](https://img.shields.io/badge/PR-Learning--Activity-yellow)
> 2. Access this year's assessment tasks, and compare it with those demonstration tasks covered in practical classes. Make a study plan for your `Pattern Classification` study, and think about forming a team for group assessment. 
### Activity 3

![GitHub watchers](https://img.shields.io/badge/PR-Learning--Activity-yellow)
> 3. Access this year's assessment tasks, and compare it with those demonstration tasks covered in practical classes. Make a study plan for your `Pattern Classification` study, and think about forming a team for group assessment. 
