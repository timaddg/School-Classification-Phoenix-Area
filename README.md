# School-Classification-Phoenix-Area

Examining the Model Performances:
1. **SVM, or support vector machine:**
- Strengths: Reasonable performance on the test set (87%) and high accuracy on the validation set (93%). Effective classification of non-class 1 examples is demonstrated by the model's high precision and recall for class 0.
- Weaknesses: Class imbalance or overfitting may be the cause of the low recall for class 1 (50%) which indicates problems in recognizing good instances of this class. –
- Model Characteristics: The use of the 'rbf' kernel indicates that SVM is skilled at handling non-linear data separations thanks to its kernel trick.
2. **ANNs, or artificial neural networks:**
- Strengths: Because of its layered structure, it can simulate complex non-linear connections with a fair average accuracy of 80.12% across folds.
- Limitations: A higher accuracy standard deviation (3.72%) across folds suggests that there may be problems with the stability of the model and its sensitivity to split data. - Characteristics of the Model: requires network architecture and training parameter adjustments that are carefully made to prevent both overfitting and underfitting.
3. **DT (Decision Tree)**:
- Strengths: Ability to give transparent decision-making procedures and good average cross-validation score (88.33%).
- Weaknesses: A sensitivity to training data splits may result in overfitting, as indicated by the variability in cross-validation scores, which range from 66.67% to 100%.
  
 
**Conclusion**: Model Characteristics: Simple to understand, but without appropriate growth limits on the model, it is prone to overfitting.
The following justifies the selection of SVM:
- High Precision and Controllable Recall Issues: - Among the models, SVM showed the
highest level of precision, particularly for class 0. The primary cause of class 1's low recall can be resolved by employing techniques like balancing the dataset by gathering additional data for class 1 or modifying class weights, which can greatly enhance model performance without sacrificing its advantages.
- Efficiency with Non-linear Information: - SVM employs the 'rbf' kernel, which enables it to manage intricate and non-linear decision boundaries with efficiency. Given that the supplementary data is assumed to enhance the feature space and provide more unpredictability, the SVM's ability to adjust for this intricacy may prove advantageous.
- Flexibility and Scalability: - Support vector machines (SVMs) are commonly employed in binary classification tasks and exhibit scalability when additional data is added, particularly when suitable kernel selections are made. Because of this, SVM is a reliable option as more data becomes accessible.
- Potential for Improved Generalization: - SVM should be able to generalize more effectively over unknown data if overfitting is appropriately adjusted for using regularization, cross-validation, and maybe redefining the kernel parameters or investigating other kernels.
- Following data recollection, particularly with a greater emphasis on class 1, the SVM model can be improved to better manage the class imbalance and possibly enhance recall and precision for class 1. The SVM is a great contender for the ongoing project phases since it can produce better generalization and robustness by fine-tuning the model parameters with the fresh, more balanced dataset. By utilizing SVM's advantages and minimizing its disadvantages, this strategy will lay a strong basis for accomplishing the project's goals.
