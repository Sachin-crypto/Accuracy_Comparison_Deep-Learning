# Comparing Accuracies of 4 Transfer Learning Models 
The most commonly used pre-trained models (VGG, Xception, Inception, and ResNet) are fine-tuned and trained on the image dataset to evaluate the accuracy.

![Deep Learning](https://img.shields.io/badge/Deep%20Learning-00b4d8)
![Keras](https://img.shields.io/badge/Keras-f72585)
![Transfer Learning](https://img.shields.io/badge/Transfer%20Learning-fb5607)

# Training for 100 Epochs
Accuracy after training models for 100 epochs.

```python
>>> Training VGG16 model:
>>> Evaluating VGG16 on the Test data:
10/10 [==============================] - 67s 7s/step
>>> Test Accuracy for VGG16: 93.00%.
>>> Training Xception model:
>>> Evaluating Xception on the Test data:
10/10 [==============================] - 1s 44ms/step
>>> Test Accuracy for Xception: 100.00%.
>>> Training InceptionV3 model:
>>> Evaluating InceptionV3 on the Test data:
10/10 [==============================] - 2s 50ms/step
>>> Test Accuracy for InceptionV3: 99.00%.
>>> Training ResNet50 model:
>>> Evaluating ResNet50 on the Test data:
10/10 [==============================] - 2s 60ms/step
>>> Test Accuracy for ResNet50: 65.00%.
```
Training and Validation Data Accuracy Plot

![100epoch](https://github.com/Sachin-crypto/Accuracy_Comparison_Deep-Learning/assets/72191416/00349e22-0adc-4155-87f0-e55e248bd418)

# Training for 10 Epochs
Accuracy after training models for 10 epochs.

```python
>>> Training VGG16 model:
>>> Evaluating VGG16 on the Test data:
10/10 [==============================] - 19s 2s/step
>>> Test Accuracy for VGG16: 91.00%.
>>> Training Xception model:
>>> Evaluating Xception on the Test data:
10/10 [==============================] - 1s 44ms/step
>>> Test Accuracy for Xception: 100.00%.
>>> Training InceptionV3 model:
>>> Evaluating InceptionV3 on the Test data:
10/10 [==============================] - 2s 55ms/step
>>> Test Accuracy for InceptionV3: 99.00%.
>>> Training ResNet50 model:
>>> Evaluating ResNet50 on the Test data:
10/10 [==============================] - 2s 45ms/step
>>> Test Accuracy for ResNet50: 62.00%.
```

Training and Validation Data Accuracy Plot

![10epochs](https://github.com/Sachin-crypto/Accuracy_Comparison_Deep-Learning/assets/72191416/06dfd4a8-2cb6-4996-a6c0-6d5ebaa28606)

