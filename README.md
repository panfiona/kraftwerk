### PCB trace impedance estimation

**Author**

#### Executive summary

#### Rationale
Why should anyone care about this question?
PCB trace impedance is a very common element and very important in PCB design. So how to estimate the impedance is significant. 

#### Research Question
What are you trying to answer?
It is known that the PCB trace impedance was determined by PCB dielectric thickness, dielectric constant, trace width and thickness. So I will explore the multiple linear regression to estimate the trace impedance by the above features. 


#### Data Sources
What data will you use to answer you question?
Use a simulation tool to generate a group of features and the corresponding impedance to these features.

#### Methodology
What methods are you using to answer the question?
Use polynomial to generate higher order of the features, and use multiple linear regression to do the estimation

#### Results
What did your research find?
Multiple linear regression is able to predict the PCB impedance from the features listed above. 

#### Next steps
What suggestions do you have for next steps?
Will need to figure out a way to sweep the features in a larger scale and train the model. 

#### Outline of project

- [https://github.com/panfiona/kraftwerk/blob/main/Capstone.ipynb]



##### Contact and Further Information