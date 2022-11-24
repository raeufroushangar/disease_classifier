# Description:

Traning and validating k-nearest neighbors model to predict the disease state (aml vs. healthy) of 613 subjects from gene expression data. KNN-Model is trained using 974 differentially expressed probe sets from 2,761 aml patients and healthy subjects in scikit-learn. Model has 97.93 (+/- 0.03) traning/validation accuracy. The data, code, and supplementary materials can all be found here.


**Confusion Matrix:**\
![AML_DiseaseSate_KNN-Classification_Trained_on_974_ProbSets_from_2761_Subjects-Confusion_Matrix](https://user-images.githubusercontent.com/39611565/203699461-f1560bf7-fb81-46e3-8eff-b61cc110d251.png)


**ROC Curve:**
![AML_DiseaseSate_KNN-Classification_Trained_on_974_ProbSets_from_2761_Subjects-ROC_Curve](https://user-images.githubusercontent.com/39611565/203697757-28c8dae5-6cc6-4cf8-89ac-d35396ea0688.png)


**Model Accuracy vs. KNN Number:**
![AML_DiseaseSate_KNN-Classification_Trained_on_974_ProbSets_from_2761_Subjects-knn_number](https://user-images.githubusercontent.com/39611565/203698301-d5473cff-ab1b-4733-8407-a3db3f775b97.png)
