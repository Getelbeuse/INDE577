# Neural Networks!

A single neuron is cool, but the human brain is made up of millions of neurons that help it function. This is the idea behind a neural network.

Dense Neural Networks, or Multilayer Perceptrons, is a parametric model of supervised learning used for both classification and regression problems. They are deep and dense because they are composed of many connected layers of single neurons, where a network of connections exist between them. They take in weights and biases, like the Perceptron, just many more!

Similarly, neural networks use a version of gradient descent as well as a version of cost difference minimization (dubbed backpropogation), varied to fit the nature of the connection density. 

Excitingly, different activation functions can be used, particularly for learning nonlinear relationships between data points. 

This notebook will include a detailed explanation of the model and will contain an application to the diabetes data set!


# The Diabetes Dataset

The Diabetes dataset is a collection of medical data from a CDC survey of Americans' health. It includes 15 variables:

1. Diabetes_012- the presence or absence of diabetes: 0= none, 1= prediabetic, 2= diabetic
2. HighBP- 0 = no high blood pressure, 1 = high blood pressure
3. HighChol- 0 = no high cholesterol 1 = high cholesterol
4. CholCheck: 0 = no cholesterol check in 5 years 1 = yes cholesterol check in 5 years
5.BMI- Body Mass Index
6. Smoker- Have you smoked at least 100 cigarettes in your entire life? 0 = no 1 = yes
7. Stroke- indicates the occurrence of a stroke.
8. HeartDiseaseorAttack- coronary heart disease (CHD) or myocardial infarction (MI) 0 = no 1 = yes
9. PhysActivity- physical activity in past 30 days - not including job 0 = no 1 = yes
10. Fruits- Consume Fruit 1 or more times per day 0 = no 1 = yes
11. Veggies- Consume Vegetables 1 or more times per day 0 = no 1 = yes
12. HvyAlcoholConsump- (adult men >=14 drinks per week and adult women>=7 drinks per week) 0 = no 1 = yes
13. AnyHealthcare- Have any kind of health care coverage, including health insurance, prepaid plans such as HMO, etc. 0 = no 1 = yes
14. NoDocbcCost- Was there a time in the past 12 months when you needed to see a doctor but could not because of cost? 0 = no 1 = yes
15. GenHlth- Would you say that in general your health is: scale 1-5 1 = excellent 2 = very good 3 = good 4 = fair 5 = poor
16. MentHlth- days of poor mental health scale 1-30 days
17. PhysHlth: Physical health status
18. DiffWalk-Do you have serious difficulty walking or climbing stairs? 0 = no 1 = yes
19. Sex- 0 = female 1 = male
20. Age- age of the individual.
21. Education- level of education attained on a scale from 1-6, where 1= never attended school
22. Income- income on a scale of 1-8





