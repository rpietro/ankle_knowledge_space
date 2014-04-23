Personalized learning pathway for ankle fractures: Semantic imaging database and knowledge space modeling using a reproducible research methodology.


Marcelo Bordalo    
Talitha Yen  
José Elvano Moraes  
Jacson Barros  
Tarcisio Barros Filho  
João Ricardo Vissoci  
Ricardo Pietrobon  


## Abstract


## Introduction

Trauma in general still constitutes one of the main reasons behind disability around the world, but with an even greater importance in developing countries and areas with a poor distribution of healthcare providers. <!-- ref --> In these locations not only the trauma incidence tends to be higher, but also because professionals with appropriate training for the diagnosis and therapeutic planning of bone fractures might not be present. Given the high degree of specialized knowledge required for these tasks, not only the risk of subsequent disability is increased <!-- ref -->, but even life threatening fractures might be missed such as in the case of cervical fractures. <!-- ref --> Despite the importance of better educating healthcare professionals regarding bone fractures, to our knowledge no open source, freely available educational technologies have been developed to address this need.

* imaging signs and fracture classification as the basis for diagnosis and therapy
* how difficult a given sign might be - prior for more sophisticated IRT models and personalized learning

The objective of this study is therefore to first create an ankle fracture imaging repository, semantically encoding imaging signs and classifications validated by a group of experts. Second, these same experts rank each sign according to a difficulty scale and encode this information into a knowledge space model used to establish an ankle fracture learning pathway.




## Methods

We first describe how the database was created, validated, and then semantically encoded. We then describe the process to model the knowledge space toward the creation of a learning pathway. 

## Database generation

* Select a group of 100 ankle fractures - DICOM for radiographs and anonymized <!-- is that possible?? -->. images selected to represent a wide range of severity
* create a checklist of common signs
* select a classification
* have a group of five specialists independently grade 60 images each, so that each image is graded by at least three specialists



## Knowledge space modeling

<!-- define with elvano -->

[R](http://www.r-project.org/) (@rcit)
<!-- packages - Elvano -->

### Reproducible research methodology
<!-- get from previous papers, vissoci paper -->
[Apache 2.0](http://www.apache.org/licenses/LICENSE-2.0.html) 
anonymized images released under a [CC license]()
scripts under [Figshare]() and [Github]()

## Results


## Discussion

* Future
	* integration [edX Code]() through [xblock]()


## References

@Manual{rcit,
    title = {R: A Language and Environment for Statistical Computing},
    author = {{R Core Team}},
    organization = {R Foundation for Statistical Computing},
    address = {Vienna, Austria},
    year = {2014},
    url = {http://www.R-project.org/},
  }