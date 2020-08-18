# Arrhythmia in Electrocardiograms
Electrocardiograms (ECG) have created a profound impact in the field
of cardiology, specifically in recognizing heart arrhythmias, a problem
with the rhythm of one’s heartbeat. Noninvasive arrhythmia analysis is
based on multiple electrodes that reflect the electrical activity on
ECGs. An estimated three million cases of arrhythmia occur in the
United States yearly (Mayo Clinic). Diagnosing this disease early is
the key to one’s wellness, yet 18% of ECGs containing Atrial
Fibrillation are misinterpreted by cardiologists (Anh et al, 2006). With
the recent advancements in technology, Machine Learning algorithms
such as Deep Neural Networks (DNNs) and Convolutional Neural
Networks (CNNs), allow a model to learn features and identify patterns
within a given dataset. Hence, making it possible to autonomously
recognize diseases in ECGs, capable of identifying arrhythmias to the
accuracy of Cardiologists.

## Description
Heart arrhythmias are irregular rhythms in heartbeats that affect 3 million
people worldwide every year. Due to the increasing rate of ECGs
recording for diagnosis, it is now possible to devolve a Convolutional
Neural Network to identify arrhythmias in ECGs. A CNN was developed
and trained, to achieve high accuracy in identifying arrhythmias in ECGs.
The 1D Convolution Neural Network not only surpassed the accuracy of
cardiologists in identifying Atrial Fibrillation, but also achieved an overall
top accuracy of 99%, and a constant accuracy of 96%. Furthermore, the
CNN was cross-validated against a new dataset that the model had
never seen before to ensure no overfitting occurred during the training
process. On this test, the CNN model achieved an accuracy of 96%. The
key to achieving such success is due to the large annotated dataset
(PhysioNet), and data augmentation techniques. Originally, training a
shallow CNN with few parameters were thought to create less complexly
in learning, and make the CNN faster in training. Doing that merely did
the opposite, as the CNN started to overfit to the training data. Adding
data augmentation not only fixed the issue of overfitting, but also
increased the dataset size; conversely, this increased the time the CNN
took to train.

## Dependencies
The following are a list of dependencies that are required to run the project:
* [Pytorch 1.4.0](https://pytorch.org/)
* [NumPy 1.18.1](https://numpy.org)
* [Matplotlib 3.1.3](https://matplotlib.org/)
* [Scipy 1.4.1](https://www.scipy.org/)
* [PyTorch 1.6.0](https://pytorch.org/)
* [h5py 2.10.0](https://www.h5py.org/)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)

## Project status
The project has been terminated (since Jan 2020).