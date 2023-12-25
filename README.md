# drone-detect

Detecting drones using audio signals is of utmost significance for enhancing safety in modern society. As drones continue to proliferate, the ability to identify and locate them through audio detection methods is crucial for military technology. Audio-based drone detection technology serves as an essential tool in safeguarding public spaces, critical infrastructure, and events, preventing security breaches, and ensuring airspace integrity. By leveraging sound analysis, it allows for the early detection and response to drones, thus mitigating potential safety risks and privacy concerns associated with their operation. This project offers an opportunity to explore audio data processing, model development, and real-world applications in audio classification.

This project was based on the [Conference Paper Here](https://www.researchgate.net/publication/332727775_Audio_Based_Drone_Detection_and_Identification_using_Deep_Learning) and Y. Zhang et al. (2017)[^1]

Libraries and Frameworks used in this project are:

* Librosa: audio processing (spectrogram) and feature extraction;
* Matplotlib: visualizing spectrograms;
* NumPy: array manipulations;
* Scikit-learn (Sklearn): data splitting and machine learning-related functionalities;
* PyTorch: building and training neural network models in Tensor format.

>[!IMPORTANT]
> The data was split into train/validation/test batches with proportions 80%:10%:10%.


I compared and evaluated the following Neural Networks for analysis and comparison:

* Convolutional Neural Network (CNN) - 95% accuracy
* Recurrent Neural Network (RNN) - 80% accuracy
* Convolutional Recurrent Neural Network (CRNN) - 75% accuracy
  
>[!NOTE]
> Evaluation Metrics used: Accuracy (In the project), Precision, Recall, F-score (Mentioned in the publication for model evaluation.)

[^1]: Y. Zhang, N. Suda, L. Lai, and V. Chandra, “Helloedge: Keyword spotting on microcontrollers,” CoRR,vol. abs/1711.07128, 2017. arXiv: 1711. 07128. [On-line]. Available: http://arxiv.org/abs/1711.07128
