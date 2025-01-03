
# A generative model of personality disorder as a relational disorder

## Introduction
This repository includes code on a model that formalizes (static) personality disorders as (dynamic) relational disorders. The model is based on the computational process of mental inference: that is, inferring the mental states that are likely to have caused one's observed behaviour (Fonagy, 1991). According to traditional psychoanalytic (e.g., object relational) and contemporary socio-cognitive (e.g., attachment and interpersonal) perspectives, mentalizing impairments are fundamental to our understanding of personality (and its putative pathology). The model embraces these perspectives and suggests that personality disorders can be more formally (and perhaps also ethically) understood as relational disorders: problems in the ways of experiencing and relating to oneself and others. Below, I outline this model of mental inference. 

## Mental Inference

![image](https://github.com/user-attachments/assets/8b770367-8570-40d8-a83a-7b6b6bd11652)

The probabilistic architecture of the model is outlined in the figure above. Essentially, the graph outlines how particular (random) variables cause (or _generate_) other (random) variables (with directed arrows indicating causality). To start from the highest to the lowest levels of the hierarchy, this generative architecture implies that (1) a set of hyperpriors (m<sub>1</sub> and m<sub>2</sub>) generate (2) a set of priors (s<sub>1</sub> and s<sub>2</sub>), which in turn generate (3) a set of observations (o<sub>1</sub> and o<sub>2</sub>). Psychologically, this generative process can be interpreted as follows: (1) Internal working models of the self (m<sub>1</sub>) and others (m<sub>2</sub>) generate (2) mental states of the self (s<sub>1</sub>) and others (s<sub>2</sub>), which in turn generate (3) observed behaviours of the self (o<sub>1</sub>) and others (o<sub>2</sub>). In other words, the model implies that internal representational concepts of ourselves and others (which have their roots in temperament and early social experience) dictate the probability of invoking (_fantasizing_ or _generating_) particular mental states that are then used as _hypotheses_ to explain observations from onself and others. 

Notably, this process is not static, but dynamic: the mental states and working models get updated over time (at times τ (fast) and t (slow), respectively), implying that a person can change their mind on _the stability of states over time_ (i.e., will a person with benevolent intensions remain benevolent at a future time point?) and _the likelihood of encountering people with certan kinds of intentions_ (i.e., are people with good intentions rare or common?). In the computational literature, these processes are known as ''learning''; here, interestingly, learning is based on social observations, suggesting that one's mental configurations (models of self / others) are fundamentally reflective of their social experience. This provides a powerful analogy to trauma-informed perspectives on personality pathology which suggest that one's ''personal'' problems are fundamentally ''social'' problems because they are predicated on maladaptive social experiences.



<p align="center">
$....$
</p>

