## Explainable Artificial Intelligence


---

| Question   | Answer                                                            |
| ---------- | ----------------------------------------------------------------- |
| Writer     | Anurag Joshi - MCA I year                                      |
| Editor     | Kajal Gupta                                                       |
| Status     | Conclusion added                                                             |
| Plagiarism| None. | [Report](./plag-reports/plag-explainableAI.pdf)
                                          

---

## Introduction

We have seen how powerful and accurate an AI system can be, but it is so, at the cost of them being black box models as they lack the virtue of explainability. Explainability in AI has become a hot topic for researchers these days. Development in explainable AI is certainly very important for us to understand and become more trustful of the decisions a machine took for us.

Explainable AI (a.k.a. XAI) is a field that is rapidly emerging nowadays. It aims to explain how “black box” AI and machine learning models are actually able to make complicated decisions for us. It is inspecting and trying to understand all the steps and models that involve decision making. And thus, it is expected of XAI to answer questions like - Why a specific AI or machine learning model makes a certain prediction? When would it fail or succeed and with what probability would it do so? Or when can we really have enough confidence in the decisions made by a machine for us?. These questions are still a few of many.

## Explainability Vs Interpretability in AI

Before we go on any further we need to understand the difference between explainability and interpretability in AI.
In the machine learning context, explainability and interpretability are generally used interchangeably. But there exist subtle differences between them that might be worth knowing about.
Interpretability can be defined as the extent to which one can predict a model’s result without trying to understand the reasons behind the predictions. So it can be said that it is easier to know the reason behind certain predictions or decisions if a model has higher interpretability. On the other hand, explainability is the extent to which the internal working of a machine learning or deep learning system can be explained to humans.
To understand the difference better, think of it like this - interpretability is about being able to know the mechanics of a model without being explicitly told and explainability is the ability to clearly explain what is happening in a model and how does it work. 

## How to achieve explainability in AI models?

Explainability in AI, in a way, can be gained by using machine learning algorithms that are inherently explainable. Algorithms like decision trees and bayesian classifiers have both traceability and transparency upto a certain level in their decision making. This could readily provide the visibility needed for AI systems without sacrificing much of accuracy or performance. But these days we have more complicated and potentially more powerful models such as neural networks, ensemble methods (e.g. random forests), that in general, sacrifice transparency and explainability for better accuracy, power and performance. Therefore, for explaining such complicated models we go for other more complex algorithmic approaches, some of which we will see below.

In order to develop explainable machine learning and deep learning systems we can use any of the two main sets of techniques; ante-hoc and post-hoc. Ante-hoc are the set of techniques which introduce explainability into a model from the very beginning. Post-hoc techniques are just the opposite of ante-hoc, that is, they allow models to be created and trained normally and only at the testing time the explainability is introduced in the mdodels.

## Ante-Hoc Methods : 

    1) Reversed Time Attention Model (RETAIN): 
    This model was created at Georgia-Tech to help doctors understand an AI software’s predictions. 
    The data of patients' hospital visits was fed to 2 RNNs equipped with attention mechanism. This exercise was conducted to understand and explain the focus points of the neural network and the features that influenced those choices.

    2) Bayesian Deep Learning (BDL): We could measure the uncertainty of a neural network’s prediction using BDL. BDL forms uncertainty estimates by either learning a direct mapping to probabilistic outputs or by placing distributions over model weights. We can figure out the path that led to the decisions taken by the model by employing weight distributions of various predictions and classes.

## Post-Hoc Methods:

    1) Local Interpretable Model-Agnostic Explanations (LIME): LIME is not confined to a single domain. This ability gives it an edge over RETAIN. LIME provides the explanation after a decision has been made, and thus can not be called a purely transparent model. For instance, in an Image classification problem (using CNN), LIME obscures different areas of the original image and feeds the result into the model to see what part of the input deviated the algorithm and derive reasoning behind such deviations.

    2) BETA: BETA is considered to be closely related to interpretable decision sets. To explain the part of the model behaviour unambiguously, BETA learns a compact 2-level decision set. BETA uses an objective function which helps the learning process in having high fidelity (agreement between explanation and model), high interpretability and low unambiguity. All these aspects are combined into one objective function which is optimized.


It has been witnessed that the success of AI models is mostly due to their complex internal representation of features, which also leads to their inexplicable nature. There are various kinds of on-going researches, even by leading companies like Google and DeepMind to make AI more answerable. But a tradeoff between accuracy and explainability will always exist. Factors like the field of application, kind of end-user and legal liabilities would weigh in. Blindly following AI systems without trying to understand the reasoning behind them is not beneficial. Interpretable and flexible AI models should be built that work well in collaboration with experts and their domain knowledge.
