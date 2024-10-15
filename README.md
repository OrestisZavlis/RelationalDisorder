
# A generative model of personality disorder as a relational disorder

## Introduction
This repository includes code on a model that formalizes (static) personality disorders as (dynamic) relational disorders. The model is based on the computational process of mental inference: that is, inferring the mental states that are likely to have caused one's observed behaviour (i.e., mentalizing; Fonagy, 1991). According to traditional psychoanalytic (e.g., object relational) and contemporary socio-cognitive (e.g., attachment and interpersonal) perspectives, mentalizing impairments are fundamental to our understanding of personality (and its putative pathology). The model embraces these perspectives and suggests that personality disorers can be more formally (and perhaps also ethically) understood as relational disorders: disordered ways of experiencing and relating to oneself and others. Below, I outline this model of mental inference. 

## Mental Inference

![image](https://github.com/user-attachments/assets/8b770367-8570-40d8-a83a-7b6b6bd11652)

The figure above outlines a probabilistic graph that defines the structure of the probabilistic model. Essentially, the graph outlines how certain (random) variables cause (_generate_) other (random) variables (with directed arrows indicating causality). To start from the highest to the lowest levels of this hierarchical model, this generative architecture implies that (1) a set of hyperpriors (m1 and m2) generates (2) a set of priors (s1 and s2), which in turn generate (3) a set of observations (o1 and o2). 

internal working models of the self and others generate (2) mental states of the self and others, which in turn (3) generate observed behaviours of the self and others. Psychologically, this process of mental inference can be recast as follows: internal working models (which have their roots in temperament and one's social experience) dictate the probability of evoking (or _fantasizing_, or _generating_) particular mental states to be used as _hypotheses_ in order to explain behaviour from oneself or others. 

~subscript~
