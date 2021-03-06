# Anemia-Detection-by-Deep-Learning
This is a modification of the previous work by using deep neural networks and it aims to detect 10 different cell types in Iron deficiency anemia, Thallasemia minor and Sickle cell anemia.
We have used the same dataset that we had for the follwoing publication:

Mahsa Lotfi, Behzad Nazari, Saeid Sadri and Nazila Karimian Sichani, "The Detection of Dacrocyte, Schistocyte and Elliptocyte Cells in Iron Deficiency Anemia"
Proceedings of 2nd International Conference on Pattern Recognition and Image Analysis (IPRIA), 2015.

In the recent modification we have used a 5 layer deep convolutional neural network to have automatic feature engineering. This architecture 
achieved 90% test accurcay and 99% training accuracy. We have used the l1-regularizer in order to penalize the weights and overcome the overfitting.

I have taken over 60 images of 10 different iron-deficient blood slides myself by using Olympus CH40RF200 microscope equipped with a Sony Full HD 1080 digital camera with an effective magnification of 100. The blood samples are taken from the Department of Medical Sciences of University of Isfahan, Iran and Sayed-Al-Shohada Hospital located at Isfahan, Iran.

My relevant paper is:
The Detection of Dacrocyte, Schistocyte and Elliptocyte cells in Iron Deficiency Anemia
https://doi.org/10.1109/PRIA.2015.7161628
