# aml-cnn
From Association of Computing Machinery Cyber x AI Lab Fall 2024.

Implemented an FGSM adversarial attack in PyTorch by training a CNN and generating imperceptibly perturbed inputs that caused controlled misclassification, strengthening understanding of ML model vulnerabilities and adversarial-robust defense.

Project-structure:  
cnn-cifar10.py (Convolutional neural networks with CIFAR-10 dataset)  
fgsm.py (Fast Gradient Sign Attack)

Here is a visualization of calculated noise produced by FGSM being applied to an input image, resulting in misclassification by the model.
<img width="639" height="271" alt="image" src="https://github.com/user-attachments/assets/0d5516bf-7a59-4605-a078-edb891470eb1" />

Visual by [TensorFlow](https://www.tensorflow.org/tutorials/generative/adversarial_fgsm).



Here is a batching visualization from running the code on Google Colab.
<img width="625" height="679" alt="Screenshot 2025-12-22 at 7 41 07 PM" src="https://github.com/user-attachments/assets/c2bec03c-c08b-4ab4-8f80-34c7f9857801" />
