
# A generative model of personality disorder as a relational disorder

## Introduction
This repository includes code on a model that formalizes (static) personality disorders as (dynamic) relational disorders. The model is based on the computational process of mental inference: that is, inferring the mental states that are likely to have caused one's observed behaviour (i.e., mentalizing; Fonagy, 1991). According to traditional psychoanalytic (e.g., object relational) and contemporary socio-cognitive (e.g., attachment and interpersonal) perspectives, mentalizing impairments are fundamental to our understanding of personality (and its putative pathology). The model embraces these perspectives and suggests that personality disorers can be more formally (and perhaps also ethically) understood as relational disorders: disordered ways of experiencing and relating to oneself and others. Below, I outline this model of mental inference. 

## Mental Inference

![image](https://github.com/user-attachments/assets/8b770367-8570-40d8-a83a-7b6b6bd11652)

The figure above outlines the probabilistic architecture of the model. Essentially, the graph outlines how particular (random) variables cause (_generate_) other (random) variables (with directed arrows indicating causality). To start from the highest to the lowest levels of this hierarchical model, this generative architecture implies that (1) a set of hyperpriors (m<sub>1</sub> and m<sub>2</sub>) generates (2) a set of priors (s<sub>1</sub> and s<sub>2</sub>), which in turn generate (3) a set of observations (o<sub>1</sub> and o<sub>2</sub>). Psychologically, this generative process can be interpreted as follows: (1) internal working models of the self and others generate (2) mental states of the self and others, which in turn generate (3) observed behaviours of the self and others. Thus, this process implies that mental representational concepts of ourselves and others (which have their roots in temperament and early social experience) dictate the probability of invoking (_fantasizing_, or _generating_) particular mental states that are then used as _hypotheses_ to explain behaviours from onself and others.  
