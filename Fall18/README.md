
### Course Information

* **Course Info:**	CS7545, Fall 2018
* **Instructor:**	Jacob Abernethy
    - **Office:** Klaus 2134
    - **Email:** prof_at_gatech_dot_edu
    - **Office Hours:** 10-11am Wednesdays in Klaus 2134
* **Course Time&Place:**	MW 4:30-5:45pm, Klaus 2443
* **Teaching Assistants**:
    - *Bhuvesh Kumar*
        - **Email:** bhuvesh_at_gatech.edu
        - **Office Hours**: Mondays 2:30-3:30pm, alcove of Klaus 2116/2124
    - *Jun-Kun Wang*
        - **Email:** jimwang_at_gatech.edu
        - **Office Hours**: Wednesdays 11am-12pm, alcove of Klaus 2116/2124


### Course Description

This course will study theoretical aspects of prediction and decision-making problems, where our goal is to understand the mathematical underpinnings of machine learning. A primary objective of the class is to bring students to the frontiers of research and to prepare students to publish in this area. The course will cover, among other things, concentration inqualities, uniform deviation bounds, Vapnik-Chervonenkis Theory, Rademacher Complexity, margin bounds, boosting, some theoretical aspects of deep learning, online learning theory, regret minimization, multi-armed bandit algorithms, and connections to convex optimization. Along the way, we may dive into several related topics, including minimax equilibrium in games, calibration, sequential portfolio selection, option pricing, and differential privacy.

**Prerequisites:** Familiarity with the analysis of algorithms, probabilistic analysis, and several similar topics. CS7641 (Machine Learning) will be quite helpful but not strictly necessary. The material is going to be about 90% "theory" and thus potential students must have a strong mathematical background. We shall rely heavily on techniques from calculus, probability, and convex analysis, but many tools will be presented in lecture.

**Coursework:** There will be 5 problem sets throughout the semester.

**Grade Breakdown:**
* 50% - *Homeworks*
* 40% - *Final Exam*
* 10% - *Participation*

**Note**: The final exam will be held on Friday, December 7, from 2:40-5:30pm.


### References:

Roughly half of the course will follow material from the following text:

 * "[Foundations of Machine Learning](https://www.amazon.com/Foundations-Machine-Learning-Adaptive-Computation/dp/026201825X)" by Mehryar Mohri, Afshin Rostamizadeh, and Ameet Talwalkar

Much of the material in online learning (aka regret minimization) is of my own taste, and I will present these topics how I enjoy. But for students that want reading material on this topic, there are several surveys releaseSd in the last several years that explore several many that we shall cover. I will link to them here, and will mention them in various lectures when appropriate:

* [The Multiplicative Weights Update Method](http://www.cs.princeton.edu/~arora/pubs/MWsurvey.pdf) by Sanjeev Arora, Elad Hazan, and Satyen Kale.
* [Online Learning and Online Convex Optimization survey](http://www.cs.huji.ac.il/~shais/papers/OLsurvey.pdf) by Shai Shalev-Shwartz.
* [The convex optimization approach to regret minimization survey](http://www.cs.princeton.edu/~ehazan/papers/OCO-survey.pdf) by Elad Hazan.
* [Sasha Rakhlin's Lecture Notes](http://www-stat.wharton.upenn.edu/~rakhlin/courses/stat928/stat928_notes.pdf).


### Scribe Notes

| Lecture | Date  | Topic |
| :------------: |:-------------: |:-------------: |
| [1](./scribe/lec1.pdf)   | 20 Aug 2018 | Introduction and norms |
| [2](./scribe/lec2.pdf)    | 22 Aug 2018 | Convex analysis |
| [3](./scribe/lec3.pdf)    | 27 Aug 2018 | Convex Analysis + Deviation Bounds |
| [4](./scribe/lec4.pdf)    | 29 Aug 2018 | Concentration Inequalities |
| [5](./scribe/lec5.pdf)    | 05 Sep 2018 | Martingales + Online Learning |
| [6](./scribe/lec6.pdf)    | 10 Sep 2018 | Multiplicative Weights |
| [7](./scribe/lec7.pdf)    | 12 Sep 2018 | EWA + Perceptron |
| [8](./scribe/lec8.pdf)    | 17 Sep 2018 | Perceptron + Game Theory |
| [9](./scribe/lec9.pdf)    | 19 Sep 2018 | Zero-sum Games + Boosting |
| [10](./scribe/lec10.pdf)  | 26 Sep 2018 | Boosting + Online Convex Optimization|
| [11](./scribe/lec11.pdf)  | 01 Oct 2018 | Online Convex Optimization |
| [12](./scribe/lec12.pdf)  | 03 Oct 2018 | Online Convex Optimization (Cont.)|
| [13](./scribe/lec13.pdf)  | 10 Oct 2018 | FTRL |
| [14](./scribe/lec14.pdf)  | 15 Oct 2018 | Multi-armed Bandits |
| [15](./scribe/lec15.pdf)  | 17 Oct 2018 | Stochastic Multi-Armed Bandits |
| [16](./scribe/lec16.pdf)  | 22 Oct 2018 | UCB algorithm |
| [17](./scribe/lec17.pdf)  | 24 Oct 2018 | Statistical Learning Theory |
| [18](./scribe/lec18.pdf)  | 29 Oct 2018 | Contextual Bandits |
| [19](./scribe/lec19.pdf)  | 31 Oct 2018 | Reinforcement Learning |
| [20](./scribe/lec20.pdf)  | 05 Nov 2018 | VC Dimension + Rademacher Complexity |
| [21](./scribe/lec21.pdf)  | 07 Nov 2018 | Growth Function and Massart’s Lemma |
| [22](./scribe/lec22.pdf)  | 12 Nov 2018 | Massart’s Lemma and Sauer’s Lemma |
| [23](./scribe/lec23.pdf)  | 14 Nov 2018 | VC-Dimension Upper & Lower Bounds |
| [24](./scribe/lec24.pdf)  | 19 Nov 2018 | Generalization Error + Margin Theory|
| [25](./scribe/lec25.pdf)  | 26 Nov 2018 | VC Dimension of Neural Networks |
| [26](./scribe/lec26.pdf)  | 28 Nov 2018 | Variational inference |

[The Latex template for scribes is available here.](./scribe/CS7545scribe_template.tex)

### Homeworks

| Homework | Due Date  | 
| :------------: |:-------------: |
| [1](./hw/hw1.pdf) | Sep 10 2018, 2:00 pm |
| [2](./hw/hw2.pdf) | Sep 24 2018, 2:00 pm |
| [3](./hw/hw3.pdf) | Oct 17 2018, 2:00 pm |
| [4](./hw/hw4.pdf) | Nov 16 2018, 4:00 pm |
| [5](./hw/hw5.pdf) | Dec 2 2018, 11:59 pm |


[The Latex template for HW submissions is available here.](./hw/CS7545hw_template.tex)

