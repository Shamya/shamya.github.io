---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

Organized by research area:
1. [Bias, Fairness, and Equity](#bias-fairness-and-equity)
2. [Affective Computing in Education](#affective-computing-in-education)
3. [Methodological Improvements: Statistics, Machine Learning, New Approaches](#methodological-improvements)
4. [Predictive Modelling Applications: Games, Identity, Affect](#predictive-modelling-applications)

For the full list of papers, please visit my [Google Scholar](https://scholar.google.com/citations?user=5w4I9VMAAAAJ) page. If the data for a paper is not made public yet, the access is restricted under IRB. 

---

## Bias, Fairness, and Equity
---
Adaptive systems in education need to ensure that their pedagogical decisions meet the needs of all students for an equitable outcome. Recent research highlights how these systems encode societal biases leading to discriminatory behaviors towards specific student subpopulations. However, the focus has mostly been on investigating bias in predictive modeling, particularly its downstream stages like model development and evaluation.

### Upstream Bias
My research on upstream bias hypothesizes that the upstream sources (i.e., theory, design, training data collection method) in the development of adaptive systems also contribute to the bias in these systems, highlighting the need for a nuanced approach to conducting fairness research. By empirically analyzing student data collected from various virtual learning environments, we investigate demographic disparities in three cases representative of the aspects that shape technological advancements in education: 1) non-conformance of data to a widely-accepted _theoretical model_ of emotion, 2) differing implications of _technology design_ on student outcomes, and 3) varying effectiveness of _methodological improvements_ in annotated data collection.
* __Karumbaiah, S.__, Baker, R.S., Ocumpaugh, J. (2021) Context Matters: Differing Implications of Motivation and Help-Seeking in Educational Technology. _International Journal of Artificial Intelligence in Education (IJAIED)_. \[[git](https://github.com/Shamya/RMDemogFairness)]
* __Karumbaiah, S.__, Baker, R.S., Ocumpaugh, J., Andres, J.M.A.L. (2021) A Re-Analysis and Synthesis of Data on Affect Dynamics in Learning. _IEEE Transactions on Affective Computing (IEEE TAC)_. \[[pdf](http://radix.www.upenn.edu/learninganalytics/ryanbaker/AffectDyanmics_IEEETAC_CameraReady.pdf)] \[[git](https://github.com/Shamya/L-Statistic-for-Transition-Likelihood.git)]
* __Karumbaiah, S.__, Lan, A., Nagpal, S., Baker, R.S., Botelho, A., Heffernan, N. (2021) Using Past Data to Warm Start Active Machine Learning: Does Context Matter? _International Learning Analytics and Knowledge Conference (ACM LAK)_. \[[pdf](https://people.umass.edu/~andrewlan/papers/21lak-warmstart.pdf)] **Nominated for Best Paper Award**

### Historical Bias
Furthermore, we argue that the historical injustices perpetuated by algorithmic systems in education are the result of the colonial ways of knowing (and being) that continue to shape them. Using three illustrative scenarios, we sociohistorically contextualize some of the fundamental principles of data and algorithms to reveal that they are still rooted in coloniality. 
* __Karumbaiah, S.__, Brooks, J. (2021) How Colonial Continuities Underlie Algorithmic Injustices in Education. _IEEE Research in Equity and Sustained Participation in Engineering, Computing, and Technology (IEEE RESPECT)_.

---

## Affective Computing in Education
---
### Affect Dynamics
Affect dynamics, the study of how affect develops and manifests over time, has become a popular area of research in affective computing for learning. In this paper, we first provide a detailed analysis of prior affect dynamics studies, elaborating both their findings and the contextual and methodological differences between these studies. We then address methodological concerns that have not been previously addressed in the literature, discussing how various edge cases should be treated.
* __Karumbaiah, S.__, Andres, J.M.A.L., Botelho, A.F., Baker, R.S., Ocumpaugh, J. (2018) The Implications of a Subtle Difference in the Calculation of Affect Dynamics. _International Conference on Computers in Education (ICCE)_. \[[pdf](http://www.upenn.edu/learninganalytics/ryanbaker/i_paper_36.pdf)] \[[git](https://github.com/Shamya/L-Statistic-for-Transition-Likelihood.git)] **Nominated for Best Paper Award**

Next, we present mathematical evidence that several past studies applied the transition metric (L) incorrectly - leading to invalid conclusions of statistical significance - and provide a corrected method.
* __Karumbaiah, S.__, Baker, R.S., Ocumpaugh, J. (2019) The Case of Self-Transitions in Affective Dynamics. _International Conference on Artificial Intelligence in Education (AIED)_. \[[pdf](http://www.upenn.edu/learninganalytics/ryanbaker/AIED2019_paper_55.pdf)] \[[git](https://github.com/Shamya/L-Statistic-for-Transition-Likelihood.git)] 

Using this corrected analysis method, we reanalyze ten past affect datasets collected in diverse contexts and synthesize the results, determining that the findings do not match the most popular theoretical model of affect dynamics. Instead, our results highlight the need to focus on cultural factors in future affect dynamics research
* __Karumbaiah, S.__, Baker, R.S., Ocumpaugh, J., Andres, J.M.A.L. (2021) A Re-Analysis and Synthesis of Data on Affect Dynamics in Learning. _IEEE Transactions on Affective Computing (IEEE TAC)_.

For methodological improvements proposed for affect dynamics research, navigate to 
* [Transition Analysis](#transition-analysis), [Epistemic Network Analysis](#epistemic-network-analysis) and [Multiple Comparisons](#multiple-comparisons).

### Affect Detection 
* Lan, A., Botelho, A., __Karumbaiah, S.__, Baker, R.S., Heffernan, N. (2020) Accurate and Interpretable Sensor-free Affect Detectors via Monotonic Neural Networks. _International Conference on Learning Analytics and Knowledge (LAK)_.
* Nye, B. D., __Karumbaiah, S.__, Tokel, S. T., Core, M. G., Stratou, G., Auerbach, D., & Georgila, K. (2018) Engaging with the Scenario: Affect and Facial Patterns from a Scenario-Based Intelligent Tutoring System. _International Conference on Artificial Intelligence in Education (AIED)_. \[[pdf](http://people.ict.usc.edu/~kgeorgila/publications/nye_aied18.pdf)] \[[git](https://github.com/benjamid/SuperLearningAnalytics.git)]
* Nye, B., __Karumbaiah, S.__, Tokel, S. T., Core, M. G., Stratou, G., Auerbach, D., & Georgila, K. (2017) Analyzing Learner Affect in a Scenario-Based Intelligent Tutoring System. _International Conference on Artificial Intelligence in Education (AIED)_. \[[pdf](http://people.ict.usc.edu/~kgeorgila/publications/nye_aied17.pdf)] \[[git](https://github.com/benjamid/SuperLearningAnalytics.git)]

### Affect Analysis
* __Karumbaiah, S.__, Lizarralde, R., Allessio, D., Woolf, B.P., Arroyo, I., Wixon, N. (2017) Addressing Student Behavior and Affect with Empathy and Growth Mindset. _International Conference on Educational Data Mining (EDM)_. \[[pdf](https://files.eric.ed.gov/fulltext/ED596572.pdf)] \[[git](https://github.com/rezecib/MathspringDataProcessing.git)]
* Ocumpaugh, J., Baker, R.S., __Karumbaiah, S.__, Crossley, S.A., Labrum, M., (2020) Affective Sequences and Student Actions Within Reasoning Mind. _International Conference on Artificial Intelligence in Education (AIED)_.
* Andres, J.M.A.L., Ocumpaugh, J., Baker, R., Slater, S., Paquette, L., __Karumbaiah, S.__, Jiang, Y., Bosch, N., Munshi, A., Moore, A., Biswas, G. (2019) Affect Sequences and Learning in Betty’s Brain. _International Conference on Learning Analytics and Knowledge (LAK)_. \[[pdf](http://www.upenn.edu/learninganalytics/ryanbaker/LAK19BettysBrainAffect.pdf)]
* __Karumbaiah, S.__, Rahimi, S., Baker, R.S., Shute, V., D’Mello, S.K. (2018) Is Student Frustration in Learning Games More Associated with Game Mechanics or Conceptual Understanding? _International Conference of the Learning Sciences (ICLS)_. \[[pdf](http://www.upenn.edu/learninganalytics/ryanbaker/ICLS-Shamya.pdf)]

---

## Methodological Improvements
---
### Active Learning
* __Karumbaiah, S.__, Lan, A., Nagpal, S., Baker, R.S., Botelho, A., Heffernan, N. (2021) Using Past Data to Warm Start Active Machine Learning: Does Context Matter? _International Learning Analytics and Knowledge Conference (ACM LAK)_. **Nominated for Best Paper Award**

### Transition Analysis
* Matayoshi, J., __Karumbaiah, S__. (2021) Using Marginal Models to Adjust for Statistical Bias in the Analysis of State Transitions. _International Learning Analytics and Knowledge Conference (LAK)_.
* Matayoshi, J., __Karumbaiah, S.__ (2020) Adjusting the L Statistic when Self-Transitions are Excluded in Affective Dynamics. _Journal of Educational Data Mining (JEDM)_.
* __Karumbaiah, S.__, Baker, R.S., Ocumpaugh, J. (2019) The Case of Self-Transitions in Affective Dynamics. _International Conference on Artificial Intelligence in Education (AIED)_. \[[pdf](http://www.upenn.edu/learninganalytics/ryanbaker/AIED2019_paper_55.pdf)] \[[git](https://github.com/Shamya/L-Statistic-for-Transition-Likelihood.git)] 

### Epistemic Network Analysis
* __Karumbaiah, S.__, Baker, R.S. (2020) Studying Affect Dynamics using Epistemic Networks. _International Conference on Quantitative Ethnography (ICQE)_. **Nominated for Best Paper Award**
* __Karumbaiah, S.__, Baker, R.S., Barany, A., Shute, V. (2019) Using Epistemic Networks with Automated Codes to Understand Why Players Quit Levels in a Learning Game. _International Conference on Quantitative Ethnography (ICQE)_. \[[pdf](http://www.upenn.edu/learninganalytics/ryanbaker/ICQE2019.pdf)]

### Multiple Comparisons
* Matayoshi, J., __Karumbaiah, S.__ (2021) Investigating the Validity of Methods Used to Adjust for Multiple Comparisons in Educational Data Mining. _International Conference on Educational Data Mining (EDM)_.

---

## Predictive Modelling Applications
---
### Learning Games
* __Karumbaiah, S.__, Baker, R.S., Shute, V. (2018) Predicting Quitting in Students Playing a Learning Game. _International Conference on Educational Data Mining (EDM)_. \[[pdf](http://www.upenn.edu/learninganalytics/ryanbaker/EDM2018_paper_39.pdf)] \[[git](https://github.com/Shamya/Quit-Prediction-Physics-Playground.git)]  **Nominated for Best Paper Award**
* __Karumbaiah, S.__, Baker, R.S., Barany, A., Shute, V. (2019) Using Epistemic Networks with Automated Codes to Understand Why Players Quit Levels in a Learning Game. _International Conference on Quantitative Ethnography (ICQE)_. \[[pdf](http://www.upenn.edu/learninganalytics/ryanbaker/ICQE2019.pdf)]

### Math Identity and Success 
* Crossley, S.A., __Karumbaiah, S.__, Ocumpaugh, J., Labrum, M., Baker, R.S. (2020) Predicting Math Identity through Language and Click-stream Patterns in a Blended Learning Mathematics Program for Elementary Students. _Journal of Learning Analytics (JLA)_.
* Crossley, S.A., __Karumbaiah, S.__, Ocumpaugh, J., Labrum, M., Baker, R.S. (2019) Predicting Math Success in an Online Tutoring System Using Language Data and Click-stream Variables: A longitudinal analysis. _Conference on Language, Data and Knowledge (LDK)_. \[[pdf](http://www.upenn.edu/learninganalytics/ryanbaker/OASIcs-LDK-2019-25.pdf)]
* __Karumbaiah, S.__, Ocumpaugh, J., Labrum, M., Baker, R.S. (2019) Temporally Rich Features Capture Variable Performance Associated with Elementary Students’ Lower Math Self-concept. Workshop on Online Learning and social-Emotional Learning at the _International Conference on Learning Analytics and Knowledge (LAK)_. \[[pdf](http://www.upenn.edu/learninganalytics/ryanbaker/LAK19SEL_paper_3.pdf)] 

### Affect Detection
* See [Affect Detection](#affect-detection)



* __Karumbaiah, S.__, Labrum, M., Ocumpaugh, J., Baker, R.S. (2019) The Influence of School Demographics on the Relationship Between Students’ Help-Seeking Behavior and Performance and Motivational Measures. _International Conference on Educational Data Mining (EDM)_. \[[pdf](http://www.upenn.edu/learninganalytics/ryanbaker/EDM2019_paper31.pdf)]
