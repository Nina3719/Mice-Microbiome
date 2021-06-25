# Mice-Microbiome

This project explores the intricacies of the microbiome. In particular, we aim to accomplish two goals: 1) classify the change in absolute abundance of a microbial taxa given one of the three perturbations and 2) classify the family of a microbial taxa given the fluctuations in absolute abundance of a microbial taxa. To accomplish the first goal we implemented several logistic regression models to forecast the effects of three different pertrubations on the microbiome system. These three perturbations were to subject the mice to either a high-fat diet, Vancomycin, or Gentamicin. For the second goal we made several recurrent networks and a convolutional neural network to help us classify the family of a particular microbial taxa, given variation in the absolute abundance. Although our neural networks provided some success, the lack of an abundant amount of data prevents our models from taking full advantage of the power of a neural net. Nevertheless, we successfully accomplished both goals.

## Authors
Nina Chen
Moni Radev
Jessica Tian
Alex Yu

## Instructors
Georg K. Gerber <ggerber@bwh.harvard.edu> \
Travis E. Gibson <tegibson@bwh.harvard.edu>

## Lecture Outline


 - __Lecture 1__:  Introduction to the microbiome

 - __Lecture 2__:  Data and time series modesl
    - *Part 1*: Details on the data
    - *Part 2*: Overview of time series models

 - __Lecture 3__: Deep dive into time series dynamical models (most likely will be recorded)



### References

* Bucci, V., Tzen, B., Li, N. *et al.* MDSINE: Microbial Dynamical Systems INference Engine for microbiome time-series analyses. *Genome Biol* __17__, 121 (2016). <https://doi.org/10.1186/s13059-016-0980-6>

* Gibson, T.E., Gerber, G.K. Proceedings of the 35th International Conference on Machine Learning, PMLR __80__:1763-1772, (2018). <http://proceedings.mlr.press/v80/gibson18a>

* Gerber, Georg K., The dynamic microbiome, *FEBS Letters*, **588**, (2014) <https://doi.org/10.1016/j.febslet.2014.02.037>


#### Notes
* Data not included for privacy reasons
