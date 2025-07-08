# rock_img_classification
Rock Classification using ResNet  This project addresses automated rock image classification leveraging deep learning, specifically using the ResNet-50 CNN architecture. We trained the model on the Kaggle "Rock Classification Dataset," performing extensive preprocessing, including duplicate removal and data augmentation. 
The model achieved around 70% validation accuracy. Evaluations included experimenting with different hyperparameters (epochs, batch sizes, optimizers). Final tests showed satisfactory real-world generalization.
Key information:

Architecture: ResNet-50 (transfer learning)

Dataset: Rock Classification Dataset (2082 images, 7 classes)

Frameworks: Python, PyTorch

Best hyperparameters: Adam optimizer, batch size 32, 20 epochs

Final accuracy: ~70% validation accuracy, 57% accuracy on unseen images

Challenges: Class imbalance, duplicate images, limited dataset diversity

Future improvements: Enhanced data augmentation, larger and more balanced datasets, advanced fine-tuning
