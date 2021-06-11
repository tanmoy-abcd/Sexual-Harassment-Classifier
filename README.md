# Sexual-Harassment-Classifier
This is a NLP project , that classifies an incident of sexual harassment to Commenting , Ogling and Groping

Sexual Harassment is a very relevant part of the current society that we live in that needs more
importance than it already gets .It is extremely important to leverage the technological
advancement that we have had over the years toward this problem and make a better
tomorrow.

My aim in this project is to use Machine Learning Algorithms to classify the text description that
the victim has experienced into category of sexual harassment (Commenting/Ogling/Groping). This is
a Multi Label Problem which means the description may belong to one class , more than one
class or no class at all.

The data is gathered from SafeCity , an indian organization that has collected real life
experience of sexually harassed victims across the world and classified them into several
categories , we are selecting (Commenting/Ogling/Groping) for the aim of our project.

Here (Commenting/Ogling/Groping) is our labels. They are binary values such that 1 depicts that ,
that certain description contains an incident of that label and 0 if not.
We can check the F1 Score ,Precision and recall for each model to evaluate its performance.
Since this is a Multi label classification problem , we will also use Hamming loss to judge the
performance of the whole model.

The model was able to attain an F1_score of 0.69 and an hamming loss of 0.16

+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

