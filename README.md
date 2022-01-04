# ### an-accelerated-classification-model-to-automatically-discriminate-between-a-signal-process
develop an implementation plan for  an  accelerated  classification  model  to  automatically  discriminate  between  a  signal  process  which  produces  Higgs  bosons  and  a  background  process  which  does  not.  In  this  coursework  you  are  required to implement your solution using the RAPIDS accelerated framework.
Detail of the tasks
1) Data pre-processing
In this task, you are required to pre-process the particle dataset in order to train a model capable 
of  distinguishing  between  a  signal  process  which  produces  Higgs  bosons  and  a  background 
process which does not. All tasks should be undertaken in Juypter Lab with a description of each 
cell using markdown. 
 Using the particle dataset (Particle.zip) on Canvas, you are required load the data set 
into an appropriate data frame. 
 Include visualisations of the data frame such as scatter plots etc.
 Investigate and implement appropriate dimensionality reduction techniques within the 
RAPIDS framework. 
 Use an appropriate technique to decide which features are important to train the model 
using the generated data.
 You will need to set your independent variable (response class).
 You are required to generate an appropriate train/test/validation split.
2) Training of accelerated ML models using RAPIDS
In this task, you are required to train a classification model using the pre-processed data from task 
1. The model architecture and hyperparameters you choose to perform the classification is 
up  to  you;  however,  you  must  provide  justification  for  your  selection  in  the  markdown.  A 
comparison  between  different  models  must  be  undertaken  and  this  should  include  a 
comparison  benchmark  between  CPU  and  GPU.  Using  your  pre-processed  data  construct  a 
Jupyter notebook to achieve the following:
 Train the model’s using the RAPIDS cuML framework.
 Set the model hyperparameters.
 Train a selection of models to determine the best algorithm.
 
3) Model evaluation
In this task you are required to evaluate your model using a variety of different metrics.  For this 
task you must undertake the following steps:
 Return the confusion matrix, sensitivity, specificity, loss and AUC values to determine the 
performance of the trained models.
 Show the benchmark performance for both CPU and GPU training cycles.
 At the end of your Jupyter Notebook in markdown discuss your results.
