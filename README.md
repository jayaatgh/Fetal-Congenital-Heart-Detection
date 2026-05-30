# Fetal-Congenital-Heart-Detection
machine learning in HealthCare

The work in this system presents an application of hybrid quantum
machine learning in medical image processing. It emphasizes on a
classification problem of histopathological cancer detection using quantum
transfer learning. Rather than using a single learning model, the work model
presented here includes multiple transfer learning models, especially
ResNet18, VGG-16, Inception v3, AlexNet and different variational quantum
circuits (VQC). As a result, we present an efficient and novel method to
develop classification models utilizing hybrid classical and quantum
computers in this Noisy Intermediate Scale Quantum (NISQ) system era. We
aspire to provide comparable prediction accuracy and high expressibility
utilizing variational quantum circuits. The framework of the presented work
model here consists of four main units. The input unit, classical transfer
learning models, VQC-based Quantum Neural Network (QNN), and classical
artificial neural network (ANN). The input unit consists of a large data set, up
to 100k images. This input data set is divided into train, test, and validation
sets. These three sets work as an input for the next unit of the presented work
model- transfer learning models, sometimes called multilayer perceptron.
The second unit of this framework is made up of pre-trained transfer learning
models [16] trained on the ImageNet data set. The features received from the
classical CNN are forwarded and processed by multiple VQCs. After
processing features on multiple VQC, we select the best VQC with the
highest expressibility. Inherently, VQCs can handle the error caused by the
quantum hardware and are used for effective computation on fault-tolerant
quantum devices and NISQ devices. The last unit of the presented
architecture is a fully connected neural network. The output of the quantum
unit (VQC based QNN) is mapped into the final output layer of this unit with
softmax activation function
