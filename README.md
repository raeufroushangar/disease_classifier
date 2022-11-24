# Description:

Traning and validating k-nearest neighbors model to predict the disease state (aml vs. healthy) of 613 subjects from gene expression data. KNN-Model is trained using 974 differentially expressed probe sets from 2,761 aml patients and healthy subjects in scikit-learn. Model has 97.93 (+/- 0.03) traning/validation accuracy. The data, code, and supplementary materials can all be found here.


**Confusion Matrix:**
![89530138-5587-4ff6-ae91-88038000caab](https://user-images.githubusercontent.com/39611565/203698831-741e21ab-da1e-4a30-9229-9a91ca6c11a6.png)


**ROC Curve:**
![AML_DiseaseSate_KNN-Classification_Trained_on_974_ProbSets_from_2761_Subjects-ROC_Curve](https://user-images.githubusercontent.com/39611565/203697757-28c8dae5-6cc6-4cf8-89ac-d35396ea0688.png)


**Model Accuracy vs. KNN Number:**
![AML_DiseaseSate_KNN-Classification_Trained_on_974_ProbSets_from_2761_Subjects-knn_number](https://user-images.githubusercontent.com/39611565/203698301-d5473cff-ab1b-4733-8407-a3db3f775b97.png)
