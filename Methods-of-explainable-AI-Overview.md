

Methods for ex-AI: Examples on GitHub

###	0 General Introduction / Overview
•	Paper: Practical Techniques for Interpreting Machine Learning Models: Introductory Open Source Examples Using Python, H2O, and XGBoost
https://fatconference.org/static/tutorials/hall_interpretable18.pdf

•	Machine Learning Interpretability (MLI) 
collection of materials illustrating applications and adaptations of the techniques for interpreting complex machine-learning models for practicing data scientists https://github.com/h2oai/mli-resources#dockerfile

###	1 Gradients

•	Grad-CAM++:
Generalized Gradient-based Visual Explanations for Deep Convolutional Networks
https://github.com/adityac94/Grad_CAM_plus_plus

•	Monotonic Gradient Boosting using XGBoost
Monotonicity is an important facet of intepretability - monotonic relationships are usually easier to explain and understand than non-monotonic relationships. 
https://github.com/h2oai/mli-resources/blob/master/notebooks/mono_xgboost.ipynb
	
### 2	Sensitivity Analysis
•	Introduction to Sensitivity Analysis – investigate whether the model behaviour and output remain stable when input is intentionally perturbed
https://github.com/h2oai/mli-resources/blob/master/notebooks/sensitivity_analysis.ipynb

### 3	Decomposition Relevance Propagation (Pixel-RP, Layer-RP, Deep Taylor Decomposition…)
•	TreeInterpreter package for interpreting scikit-learn’s decision tree and random forest preditions
https://github.com/andosa/treeinterpreter

### 4	Optimization (LIME model agnostic, BETA transparent approximation…)
•	Lime For Time:
application of the LIME algorithm to time series classification. The goal is to explain time series classification algorithms by highlighting the areas of the timeseries used by the classifier in its prediction.
https://github.com/emanuel-metzenthin/Lime-For-Time
•	LIME variant
Instead of perturbing a sample of interest to create a local region in which to fit a linear model, these examples use a practical sample, say all one story homes, from the data to create an approximately local region in which to fit a linear model.
https://github.com/h2oai/mli-resources/blob/master/notebooks/lime.ipynb
•	Original LIME approach
https://github.com/marcotcr/lime
•	ELI5 – a Python package which helps to debug machine learning classifiers and explain their predictions
https://github.com/TeamHG-Memex/eli5
	
### 5	Deconvolution and Guided Backpropagation
•	Contrastive Excitation Backpropagation
to visualize what causes a given neuron to fire
https://github.com/greydanus/excitationbp
	
### 6	Model Understanding

(Feature visualisation, Inverting CNN; Qualitative Testing with Concept Activation Vectors TCAV; Network Dissection)

#### Concept Activation Vectors (CAV)



### 7	Other Methods
•	Anchors explanation algorithm for machine learning models that uses rules to explain machine learning preditions

https://github.com/viadee/javaAnchorExplainer  
https://github.com/viadee/xai_examples  
https://github.com/viadee/javaAnchorServer  
Paper: Anchors: High-Precision Model-Agnostic Explanations  
https://homes.cs.washington.edu/~marcotcr/aaai18.pdf  

•	MEGA Multi-model Explanation Generation Algorithm
Paper: Balancing Explicability and Explanations – Emergent Behaviours in Human-Aware Planning 
https://arxiv.org/pdf/1708.00543.pdf ; https://www.aaai.org/ocs/index.php/FSS/FSS17/paper/viewFile/16030/15288 
http://ifaamas.org/Proceedings/aamas2018/pdfs/p2180.pdf
Explanations in Multi-Model Planning
https://github.com/TathagataChakraborti/mmp
•	Partial Dependence and ICE Plots:
Paper: Peeking inside the black box: Visualizing statistical learning with plots of individual conditional expectation. https://arxiv.org/pdf/1309.6392.pdf 
https://github.com/h2oai/mli-resources/blob/master/notebooks/pdp_ice.ipynb
•	LOCO (leave one covariance out)Technique to calculate the local contribution each input variable makes toward each model prediction
https://github.com/h2oai/mli-resources/blob/master/notebooks/loco.ipynb
•	SHAP (Shapley Additive exPlanations) a unified approach to explain the output of any machine learning model; SHAP connects game theory with local explanations and several previous methods
https://github.com/slundberg/shap
•	
