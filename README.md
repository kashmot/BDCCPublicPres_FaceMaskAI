# BDCCPublicPres_FaceMaskAI
BDCC Public Presentation with Norman Lapid, Mark Acot and Pauline Guevara

Executive Summary

Using the latest tools to process big data consisting of about 84GB in images, combined with the power of deep learning techniques in computer vision, a model that can accurately detect whether a person is WEARING A MASK, HAS AN INCORRECTLY WORN MASK, or HAS NO MASK at all is proposed. The final model has a weight of just 800 KB, which can be easily deployed at scale in any setting or device.

The project demonstrates the usage of Amazon Web Services (AWS) Elastic MapReduce (EMR) and Spark's MLlib to do big data classification. Transfer Learning was explored and a pre-trained deep learning model was used to convert the raw data to features that will be used to train some classic machine learning (ML) models. The best model was Logistic Regression as it gave the highest accuracy with 88.4% on the test set, higher than the 1.25 x PCC's 41.68%. The model was also able to make predictions for new and unseen images.
