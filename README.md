# Model Interpretation

This repository is storing the Jupyter notebook and HTML files, with the notebook explaining the method and walkthrough on how we can explain and interpret the machine learning model (or so-called **blackbox model**).

<br>

### Quick glance

The __explanability__ and __interpretability__ has become one of the hot topics in the real world (see some news below). We know what is predicted, but now we want to know why prediction is made. Knowing the why can essentially lead us to understand the source of the problem (why do we build the model in the first place) and help preventing it from the start.

Normally, we will view the interpretation as __two-main classes__: local and global.
- __Local interpretability__: provide detailed explanations of how each individual prediction was made. This will help the users to trust our model and understand how the model / recommendations are being made.
- __Global interpretability__: provide overall understanding of the structure of the model, how the model works in general. This is more important for senior or sponsors needing to understand the model at high level.

In the notebook, following methods are covered:
1. Feature importance
2. eli5
3. PDP
4. SHAP
5. LIME

