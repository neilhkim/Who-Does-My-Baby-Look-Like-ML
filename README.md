# Who Does my Baby Look Like? A Machine Learning's Answer to Family Resemblance

## Objective
The goal of this project is to provide my newborn baby's picture and see what the trained model thinks about the picture—does the baby resemble me more or my wife? Sure, friends and family have their opinions, but why leave such an important question to chance (or my sister's biased eye)?

By leveraging the power of **deep learning** and **facial recognition**, I’ll train a neural network to settle the debate once and for all: is the baby a mini-me or more of a mama’s look-alike? We'll take the science of face recognition into the exciting world of family resemblance.

### Here's the Plan:
- **Step 0**: Collect the data the model will be trained on.
- **Step 1**: Train a basic CNN model to distinguish between my face and my wife’s face.
- **Step 2**: Use this model to analyze our baby's features and decide who the baby takes after. - Plot the distribution of scores (under 0.5 means he resembles me, over 0.5 means he resembles my wife).
- **Step 3**: See how the pictures cluster. - Using Kmeans clustering.
---- 
(optional)
- **Step 4**: Expand the training dataset to include the pictures of the baby's maternal and paternal grand parents and see if the baby resembles them more than me and my wife. 

Will our baby’s face an equal blend me and my wife's faces or a carbon copy of one parent? Perhaps he will resemble his grandparent more? Let's hear what the algorithm has to say.