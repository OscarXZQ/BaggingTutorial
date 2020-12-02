# cs189 project Week 7: Bagging

<b>Navigating the file:</b>    
<br/>
This repository will help students wil prior experience with EE16A, EE16B, CS61B to learn the concept of bagging. 
The repository consists of the following items. Please click on the corresponding items to access/download the files.  
1. Slide deck on Bagging in pdf form (Bagging_Slides.pdf)  
1. Note on Bagging in pdf form (Bagging_Notes.pdf)  
1. Ipynb notebook of a working coding assignment for students to do in approximately 8-9 hours (Bagging_code_assignment.ipynb)
1. Ipynb notebook of solutions for the coding assignment (Bagging_code_solution.ipynb)
1. Quiz questions (Bagging_Quiz.pdf)  
1. A dataset you will work with through the code assignment (Admission.csv)

As a student, you will first read through the Notes.pdf and gain a theoretical knowledge of bagging related concepts. Then, you can take a quick quiz to check your basic understanding of the key concepts. The slide deck will also help you gain an overarching understanding of the material. The coding assignment is for you to get your hands dirty. You will implement naive polynomial regression bagging to more sophisticated random forest. After you did your work check your answers with solution.  


<b>Learning Objective:</b>   

The lecture note is theoretically based and aims to connect pieces of machine learning concepts related to bagging together for the student. The note reviews machine learning concepts such as bias and variance, overfitting, bootstrapping, and lead naturally to the idea of aggregated bootstrapping - bagging, in the end. Our goal is to let the student discover the internal relationship between machine learning concepts and derive the idea of bagging under our guidance. At the beginning of the note, we direct the students to a category of machine learning methods that deal with multiple learners: the ensemble family. As a foreshadowing, we also direct to the original paper of bagging and encourage them to skim it in an attempt to develop the paper reading and skimming skills of the students. We then pose meaningful bagging questions for the student to think along throughout the whole learning process. Students will then see familiar terms such as bias and variance, bootstrap, and k-fold validation and think about the ensemble method to counter overfitting. This naturally leads the way to bagging. Finally, an actual bagging example, the random forest is introduced in the end, with a slight recap of the decision tree.  

The lecture slide deck is a high-level summary of the notes. The slide deck starts off with a larger category machine learning method: ensemble. Then we direct students to the problem of overfitting with a recap on bias and variance decomposition. We included a probability review so that students can better understand the math derivation. Students will then see that bagging as an ensemble method can reduce variance while maintaining bias, which tackles the overfiting problem. Students will also have a review on the idea of bootstrapping and compare it to k-fold cross-validation. In the end, students will also implement bagging on the decision tree and develop the method: random forest.  

The coding assignment is designed for students new to 189 level of machine learning. The code assignment contains both regression and classification example, real-life dataset as well as the hypothetical dataset. The code assignment will start off with a machine learning basic recap to give ML new learners a general context. Students will practice data visualization so that they can comment on their working example later on. Then, students will code up an empirical visualization of bias and variance given different degrees of polynomials. The student will exercise the concept of bagging here to observe the performance of bagged regression in the polynomial cases where they will also examine the observation with bagging theory. In the test of the coding assignment, we bring in our dataset on admission statistics so that students will have a taste of working with real life data. We choose graduate admission statistics since it is quite relevant for students who want to pursue grad school in machine learning. The student will use pandas data frame to do bootstrap, sample, and k-fold cross-validation. Finally, the student will implement a decision tree and bagged a random forest to compare the results. The student will learn to masters the ground-up building of bagging algorithm as well as efficient library usage.


