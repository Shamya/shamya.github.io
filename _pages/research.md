---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

This page is organized by research area:
1. [Bias, Fairness, and Equity](#bias-fairness-and-equity)
2. [Affective Computing in Education](#affective-computing-in-education)
3. [Predictive Modelling Applications: Games, Identity, Affect](#predictive-modelling-applications)
4. [Methodological Improvements: Statistics, Machine Learning](#methodological-improvements)

For the full list of papers, please visit my [Google Scholar](https://scholar.google.com/citations?user=5w4I9VMAAAAJ) page. If the data for a paper is not made public yet, the access is restricted under IRB - reach out to discuss options.

---

## Bias, Fairness, and Equity
---
Adaptive systems in education need to ensure that their pedagogical decisions meet the needs of all students for an equitable outcome. Recent research highlights how these systems encode societal biases leading to discriminatory behaviors towards specific student subpopulations. However, the focus has mostly been on investigating bias in predictive modeling, particularly its downstream stages like model development and evaluation.

### Upstream Bias
My research on upstream bias hypothesizes that the upstream sources (i.e., theory, design, training data collection method) in the development of adaptive systems also contribute to the bias in these systems, highlighting the need for a nuanced approach to conducting fairness research. By empirically analyzing student data collected from various virtual learning environments, we investigated demographic disparities in three cases representative of the aspects that shape technological advancements in education: 

1) __differing implications of _technology design_ on student outcomes__: Help-seeking and motivation have been widely studied since the early days of adaptive EdTech design for their important but complex role in learning. However, past research has often taken a cognitive approach - for example, focusing on how or when students seek help but not as much on who chooses to seek help. By studying the conditions under which the relationships between students’ behavior, motivation, and outcomes vary across different demographic contexts, we challenge implicit assumptions of generalizability in design choices, especially to the student populations currently under-studied in bias evaluation (e.g., students with low economic status, English as a second language, special education). We also demonstrate the use of publicly-available, school-level demographics for bias research where there is often access to larger and more diverse samples of student data (compared to small-scale experiments or larger convenience sampling from a homogeneous student group), but individual student demographics may be difficult or impossible to acquire.
* __Karumbaiah, S.__, Baker, R.S., Ocumpaugh, J. (2021) Context Matters: Differing Implications of Motivation and Help-Seeking in Educational Technology. _International Journal of Artificial Intelligence in Education (IJAIED)_. \[[pdf](../files/IJAIED_FATE_RMDemog.pdf)] \[[git](https://github.com/Shamya/RMDemogFairness)]

2) __non-conformance of data to a widely-accepted _theoretical model_ of emotion__: In this work, we empirically tested the generalizability of a highly-cited theoretical model of affect dynamics that is often used in affect research and design of interventions in adaptive systems. First, a systematic literature review revealed that studies that do show some evidence for the theoretical model were all conducted in the United States with undergraduate populations. To better understand its scope of applicability, we analyzed ten past affect datasets collected in diverse contexts and found that the theoretical model has a more limited scope than what it is currently being used for. The results suggest that affective patterns seem to differ based on the country in which the research was conducted (US vs. Philippines), highlighting the need to focus on cultural differences in using this theory.
* __Karumbaiah, S.__, Baker, R.S., Ocumpaugh, J., Andres, J.M.A.L. (2021) A Re-Analysis and Synthesis of Data on Affect Dynamics in Learning. _IEEE Transactions on Affective Computing (IEEE TAC)_. \[[pdf](http://radix.www.upenn.edu/learninganalytics/ryanbaker/AffectDyanmics_IEEETAC_CameraReady.pdf)] \[[git](https://github.com/Shamya/L-Statistic-for-Transition-Likelihood.git)]

3) __varying effectiveness of _methodological improvements_ in annotated data collection__: New methods are emerging in learning analytics to make collecting data, building models, and visualizing results more efficient. In this work, we examine the demographic disparity in the effectiveness of one such methodological improvement in annotated data collection. Active learning - a subfield of machine learning - has been proposed to improve annotated data collection for complex constructs like affect. However, in practice, this method suffers from the cold-start problem where it does not have access to sufficient data yet to learn from. We devised an approach to use past affect data to overcome this limitation. More importantly, we conducted experiments to show that mismatches in the urbanicity (urban vs. suburban) of the past data and target student population could be detrimental to effective modelling and provided recommendations to mitigate this disparity.
* __Karumbaiah, S.__, Lan, A., Nagpal, S., Baker, R.S., Botelho, A., Heffernan, N. (2021) Using Past Data to Warm Start Active Machine Learning: Does Context Matter? _International Learning Analytics and Knowledge Conference (ACM LAK)_. \[[pdf](https://people.umass.edu/~andrewlan/papers/21lak-warmstart.pdf)] **Nominated for Best Paper Award**

For a sumamry of these three studies, see poster [here](https://drive.google.com/file/d/1n2E3AJjlevMDR4OkuSrRSBWlgq5epbUC/view?usp=sharing).

### Historical Bias
I argue that some biases are also rooted deeply in the fundamental principles of data and algorithms. By sociohistorically contextualizing three illustrative scenarios, we assert in this paper that historical injustices perpetuated by algorithmic systems in education are the result of the colonial epistemologies that continue to shape them. 
* __Karumbaiah, S.__, Brooks, J. (2021) How Colonial Continuities Underlie Algorithmic Injustices in Education. _IEEE Research in Equity and Sustained Participation in Engineering, Computing, and Technology (IEEE RESPECT)_. \[[pdf](http://respect2021.stcbp.org/wp-content/uploads/2021/05/201_Position_Papers_01_paper_73.pdf)]

---

## Affective Computing in Education
---
### Affect Dynamics
Student affect in adaptive systems has been shown to correlate with a range of important educational constructs. Affect dynamics, the study of how affect develops and manifests over time, has become a popular area of research in affective computing for learning. Few empirical studies, however, have matched the predictions of the most commonly-cited theoretical model of affect dynamics. We first analyzed the prior empirical studies, elaborating both their findings and the contextual and methodological differences between these studies. We also addressed some methodological concerns that have not been previously addressed in the literature, discussing how various edge cases should be treated.
* __Karumbaiah, S.__, Andres, J.M.A.L., Botelho, A.F., Baker, R.S., Ocumpaugh, J. (2018) The Implications of a Subtle Difference in the Calculation of Affect Dynamics. _International Conference on Computers in Education (ICCE)_. \[[pdf](http://www.upenn.edu/learninganalytics/ryanbaker/i_paper_36.pdf)] \[[git](https://github.com/Shamya/L-Statistic-for-Transition-Likelihood.git)] **Nominated for Best Paper Award**

Next, we presented mathematical evidence that several past studies applied the transition metric incorrectly - leading to invalid conclusions of statistical significance - and provided a corrected method.
* __Karumbaiah, S.__, Baker, R.S., Ocumpaugh, J. (2019) The Case of Self-Transitions in Affective Dynamics. _International Conference on Artificial Intelligence in Education (AIED)_. \[[pdf](http://www.upenn.edu/learninganalytics/ryanbaker/AIED2019_paper_55.pdf)] \[[git](https://github.com/Shamya/L-Statistic-for-Transition-Likelihood.git)] 

Using this corrected analysis method, we reanalyzed ten past affect datasets collected in diverse contexts and synthesized the results, determining that the findings do not match the most popular theoretical model of affect dynamics. Instead, our results highlights the need to focus on cultural factors in future affect dynamics research.
* __Karumbaiah, S.__, Baker, R.S., Ocumpaugh, J., Andres, J.M.A.L. (2021) A Re-Analysis and Synthesis of Data on Affect Dynamics in Learning. _IEEE Transactions on Affective Computing (IEEE TAC)_. \[[pdf](http://radix.www.upenn.edu/learninganalytics/ryanbaker/AffectDyanmics_IEEETAC_CameraReady.pdf)]

For my work on methodological improvements in affect dynamics research, see: 
* [Transition Analysis](#transition-and-sequence-analysis) and [Multiple Comparisons](#multiple-comparisons).

### Affect Analysis
I analyzed student affect data to better understand its role in student learning and experience, including a randomized controlled study on an affective intervention and a study on the relationship between affect and game design.
* __Karumbaiah, S.__, Lizarralde, R., Allessio, D., Woolf, B.P., Arroyo, I., Wixon, N. (2017) Addressing Student Behavior and Affect with Empathy and Growth Mindset. _International Conference on Educational Data Mining (EDM)_. \[[pdf](https://files.eric.ed.gov/fulltext/ED596572.pdf)] \[[git](https://github.com/rezecib/MathspringDataProcessing.git)]
* Ocumpaugh, J., Baker, R.S., __Karumbaiah, S.__, Crossley, S.A., Labrum, M., (2020) Affective Sequences and Student Actions Within Reasoning Mind. _International Conference on Artificial Intelligence in Education (AIED)_. \[[pdf](https://www.researchgate.net/publication/342676738_Affective_Sequences_and_Student_Actions_Within_Reasoning_Mind)]
* __Karumbaiah, S.__, Rahimi, S., Baker, R.S., Shute, V., D’Mello, S.K. (2018) Is Student Frustration in Learning Games More Associated with Game Mechanics or Conceptual Understanding? _International Conference of the Learning Sciences (ICLS)_. \[[pdf](http://www.upenn.edu/learninganalytics/ryanbaker/ICLS-Shamya.pdf)]

### Affect Detection 
I designed and developed algorithms for automated affect detection in diverse learning systems using physiological sensors and interaction log data. I also developed the server-side software for an app that identifies and alerts field interviewers to critical affective moments during a student's learning with an artificially intelligent learning system. 
* Nye, B. D., __Karumbaiah, S.__, Tokel, S. T., Core, M. G., Stratou, G., Auerbach, D., & Georgila, K. (2018) Engaging with the Scenario: Affect and Facial Patterns from a Scenario-Based Intelligent Tutoring System. _International Conference on Artificial Intelligence in Education (AIED)_. \[[pdf](http://people.ict.usc.edu/~kgeorgila/publications/nye_aied18.pdf)] \[[git](https://github.com/benjamid/SuperLearningAnalytics.git)]
* Nye, B., __Karumbaiah, S.__, Tokel, S. T., Core, M. G., Stratou, G., Auerbach, D., & Georgila, K. (2017) Analyzing Learner Affect in a Scenario-Based Intelligent Tutoring System. _International Conference on Artificial Intelligence in Education (AIED)_. \[[pdf](http://people.ict.usc.edu/~kgeorgila/publications/nye_aied17.pdf)] \[[git](https://github.com/benjamid/SuperLearningAnalytics.git)]
* Andres, J.M.A.L., Ocumpaugh, J., Baker, R., Slater, S., Paquette, L., __Karumbaiah, S.__, Jiang, Y.,
Bosch, N., Munshi, A., Moore, A., Biswas, G. (2019) Affect Sequences and Learning in Betty’s Brain. _International Conference on Learning Analytics and Knowledge (LAK)_. \[[pdf](https://dl.acm.org/doi/pdf/10.1145/3303772.3303807)]
* Lan, A., Botelho, A., __Karumbaiah, S.__, Baker, R.S., Heffernan, N. (2020) Accurate and Interpretable Sensor-free Affect Detectors via Monotonic Neural Networks. _International Conference on Learning Analytics and Knowledge (LAK)_. \[[pdf](https://par.nsf.gov/servlets/purl/10191713)]

---

## Predictive Modelling Applications
---
### Learning Games
When a student is struggling in a learning game, a relevant and timely intervention could keep the student motivated and prevent frustration from leading the student to give up. However, it may be undesirable – even demotivating and harmful to learning – if the student is provided with scaffolding when they do not need it. As such, we developed a model to detect whether a student is likely to give up and quit a level in progress to identify opportunities to intervene meaningfully with supports aimed at improving student learning and engagement. 
* __Karumbaiah, S.__, Baker, R.S., Shute, V. (2018) Predicting Quitting in Students Playing a Learning Game. _International Conference on Educational Data Mining (EDM)_. \[[pdf](http://www.upenn.edu/learninganalytics/ryanbaker/EDM2018_paper_39.pdf)] \[[git](https://github.com/Shamya/Quit-Prediction-Physics-Playground.git)]  **Nominated for Best Paper Award**

While predicting when a student is likely to quit is important, it is also crucial to understand _why_ the student is likely to quit in order to inform the design of supports that address students’ individual needs. Using automatically generated events in the interaction log as codes, we study how the temporal interconnections between the events are different for students who quit and those who did not. Our analysis revealed a set of themes that point at some potential root causes for why students quit a game level unsolved.
* __Karumbaiah, S.__, Baker, R.S., Barany, A., Shute, V. (2019) Using Epistemic Networks with Automated Codes to Understand Why Players Quit Levels in a Learning Game. _International Conference on Quantitative Ethnography (ICQE)_. \[[pdf](http://www.upenn.edu/learninganalytics/ryanbaker/ICQE2019.pdf)]

### Math Identity and Success 
Math identity — the degree to which one considers oneself a “math person” — has been researched to better understand what drives students to enter STEM fields. Using text mining, click-stream analysis, and temporal analysis, we developed models of students' math success and math identity. 
* Crossley, S.A., __Karumbaiah, S.__, Ocumpaugh, J., Labrum, M., Baker, R.S. (2020) Predicting Math Identity through Language and Click-stream Patterns in a Blended Learning Mathematics Program for Elementary Students. _Journal of Learning Analytics (JLA)_. \[[pdf](https://files.eric.ed.gov/fulltext/EJ1251554.pdf)]
* Crossley, S.A., __Karumbaiah, S.__, Ocumpaugh, J., Labrum, M., Baker, R.S. (2019) Predicting Math Success in an Online Tutoring System Using Language Data and Click-stream Variables: A longitudinal analysis. _Conference on Language, Data and Knowledge (LDK)_. \[[pdf](http://www.upenn.edu/learninganalytics/ryanbaker/OASIcs-LDK-2019-25.pdf)]
* __Karumbaiah, S.__, Ocumpaugh, J., Labrum, M., Baker, R.S. (2019) Temporally Rich Features Capture Variable Performance Associated with Elementary Students’ Lower Math Self-concept. Workshop on Online Learning and social-Emotional Learning at the _International Conference on Learning Analytics and Knowledge (LAK)_. \[[pdf](http://www.upenn.edu/learninganalytics/ryanbaker/LAK19SEL_paper_3.pdf)] 

More importantly, we demonstrated that the relationship between a predictor variable (e.g., number of hints used) and the outcome of interest (math self-concept, which is an affective measure of students’ perception of their own cognitive ability) varies significantly based on the context. Such demographic differences are likely to limit the generalizability of the models of math identity.  
* __Karumbaiah, S.__, Ocumpaugh, J., Baker, R.S. (2019) The Influence of School Demographics on the Relationship Between Students’ Help-Seeking Behavior and Performance and Motivational Measures. _International Conference on Educational Data Mining (EDM)_. \[[pdf](http://www.upenn.edu/learninganalytics/ryanbaker/EDM2019_paper31.pdf)]

### Affect Detection
* See [Affect Detection](#affect-detection)

---

## Methodological Improvements
---
Part of my research also focuses on methodological innovations in statistics and machine learning. Most of this work is inspired by the challenges I encountered in using existing methods to conduct my primary research with education data. 

### Transition and Sequence Analysis
For around a decade, the L statistic has been used to evaluate the probability of transitions between states (or events). However, we found that a minor pre-processing step (excluding self-transitions), used in many papers, leads to a violation of the assumption of independence in L. We provided a simple correction to fix this statistical bias.
* __Karumbaiah, S.__, Baker, R.S., Ocumpaugh, J. (2019) The Case of Self-Transitions in Affective Dynamics. _International Conference on Artificial Intelligence in Education (AIED)_. \[[pdf](http://www.upenn.edu/learninganalytics/ryanbaker/AIED2019_paper_55.pdf)] \[[git](https://github.com/Shamya/L-Statistic-for-Transition-Likelihood.git)] 

Although the previous solution attended to the primary statistical error, it made the statistic difficult and non-intuitive to interpret. Motivated by this challenge, we proposed a modified version of the statistic (L*) that fixed the bias by definition.
* Matayoshi, J., __Karumbaiah, S.__ (2020) Adjusting the L Statistic when Self-Transitions are Excluded in Affective Dynamics. _Journal of Educational Data Mining (JEDM)_. \[[pdf](https://jedm.educationaldatamining.org/index.php/JEDM/article/view/478/125)] \[[git](https://github.com/jmatayoshi/affect-transitions)]

However, our previous study also discovered further issues with the L statistic involving states with high base rates. Another simulation study (Bosch & Paquette, 2021) reported issues with shorter sequences. These continuing issues
with the L statistic suggested that an alternate approach may be warranted. We presented two alternative procedures to conduct transition analysis that attempt to address these problems using: 1) epistemic network analysis and 2) marginal models.
* __Karumbaiah, S.__, Baker, R.S. (2020) Studying Affect Dynamics using Epistemic Networks. _International Conference on Quantitative Ethnography (ICQE)_. \[[pdf](http://radix.www.upenn.edu/learninganalytics/ryanbaker/AffectDynamicsENA_ICQE_CameraReady.pdf)] **Nominated for Best Paper Award**
* Matayoshi, J., __Karumbaiah, S__. (2021) Using Marginal Models to Adjust for Statistical Bias in the Analysis of State Transitions. _International Learning Analytics and Knowledge Conference (LAK)_. \[[pdf](https://dl.acm.org/doi/pdf/10.1145/3448139.3448182?casa_token=cnlr7hWPvQsAAAAA:HyO8oSKneiTFL_egMyWSal8trStAOpxSKznFZfsuiOdg_BycI8uIS2bh22EqygzTjhK1z3yop75REg)] \[[git](https://github.com/jmatayoshi/sequence-analysis)]

### Active Machine Learning
Active (machine) Learning (AL) methods have been explored in education to improve the data labeling efficiency. However, due to the complexity of educational constructs and data, AL has suffered from the cold-start problem where the model does not have access to sufficient data yet. We experimented the use of past data to overcome this issue and found that it could be effective based on the target student population.
* __Karumbaiah, S.__, Lan, A., Nagpal, S., Baker, R.S., Botelho, A., Heffernan, N. (2021) Using Past Data to Warm Start Active Machine Learning: Does Context Matter? _International Learning Analytics and Knowledge Conference (ACM LAK)_. \[[pdf](https://people.umass.edu/~andrewlan/papers/21lak-warmstart.pdf)] **Nominated for Best Paper Award**

### Multiple Comparisons
Research studies with education data often involve several variables related to student learning activities making it necessary to run multiple statistical tests simultaneously. We investigated the validity of methods used to adjust for false discoveries, showing that a frequently used procedure (Benjamini-Hochberg) may not be appropriate for two common scenarios in educational data mining, and recommend an alternate procedure (Benjamini-Yekutieli).
* Matayoshi, J., __Karumbaiah, S.__ (2021) Investigating the Validity of Methods Used to Adjust for Multiple Comparisons in Educational Data Mining. _International Conference on Educational Data Mining (EDM)_. \[[pdf](https://educationaldatamining.org/EDM2021/virtual/static/pdf/EDM21_paper_10.pdf)] \[[git](https://github.com/jmatayoshi/multiple-comparisons)]

---
