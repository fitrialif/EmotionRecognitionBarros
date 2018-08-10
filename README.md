This repository holds the models and solutions developed by Pablo Barros based on emotion recognition and learning.

The KEF framework was developed to facilitate the planing and fast prototyping of different scientific experiments. All the examples in this repository use the KEF framework.



**Prerequisites**


tensorflow-gpu </br>

keras</br>

matplotlib</br>

h5py</br>

opencv-python</br>

librosa</br>

pillow</br>

imgaug</br>

python_speech_features</br>

hyperas </br>


**Instructions**

Each of the examples here run within the KEF framework. Also, each example needs a specific dataset which is not available here.


**Hand gesture recognition**

- NCD_VisionNetwork_SobelXY.py: Audio Channel for the OMG-Emotion dataset (Barros et al., 2014)

**Auditory emotion recognition**

- OMG_Emotion_Audio_MelSpectrum.py: Audio Channel for the OMG-Emotion dataset (Barros et al., 2018)
- RAVDESS_Audio_MelSpectrum_Channel.py: Audio Channel for the RAVDESS dataset (Barros et al., 2018)

**Visual emotion recognition**

- OMG_Emotion_Face.py: Face Channel for the OMG-Emotion dataset (Barros et al., 2018)
- FERPlus_Vision_FaceChannel.py: Face Channel for the FERPlus dataset (Barros et al., 2018)

**Crossmodal emotion recognition**

- OMG_Emotion_Crossmodal.py: Cross Channel for the OMG-Emotion dataset (Barros et al., 2018)
- RAVDESS_CrossNetwork_MelSpectrum_Channel.py: Cross Channel for the RAVDESS dataset (Barros et al., 2018)



**Trained Models**

 Each of the examples has a pre-trained model associated with it. Please refer to the TrainedModels folder.



**Ready to Run Demos**

 Visual Emotion Recognition  
 - [Link](https://github.com/knowledgetechnologyuhh/EmotionRecognitionBarros/tree/master/Demos/VisualEmotionRecognition)
 - Reference:  
   Barros, P., & Wermter, S. (2016). Developing crossmodal expression recognition based on a deep neural model. Adaptive behavior, 24(5), 373-396. http://journals.sagepub.com/doi/full/10.1177/1059712316664017


**Important references**

 - Barros, P., Barakova, E., & Wermter, S. (2018). A Deep Neural Model Of Emotion Appraisal. arXiv preprint arXiv:1808.00252.
 - Barros, P., & Wermter, S. (2016). Developing crossmodal expression recognition based on a deep neural model. Adaptive behavior, 24(5), 373-396. http://journals.sagepub.com/doi/full/10.1177/1059712316664017
 - Barros, P., & Wermter, S. (2017, May). A self-organizing model for affective memory. In Neural Networks (IJCNN), 2017 International Joint Conference on (pp. 31-38). IEEE.
 - Barros, P., Jirak, D., Weber, C., & Wermter, S. (2015). Multimodal emotional state recognition using sequence-dependent deep hierarchical features. Neural Networks, 72, 140-151.
 - Barros, P., Magg, S., Weber, C., & Wermter, S. (2014, September). A multichannel convolutional neural network for hand posture recognition. In International Conference on Artificial Neural Networks (pp. 403-410). Springer, Cham.
 - [All the references](https://scholar.google.com/citations?user=LU9tpkMAAAAJ)


**License**

All the examples in this repository are distributed under the Creative Commons CC BY-NC-SA 3.0 DE license. If you use this corpus, you have to agree with the following itens:

- To cite our associated references in any of your publication that make any use of these examples.
- To use the corpus for research purpose only.
- To not provide the corpus to any second parties.

**Contact**

Pablo Barros - barros@informatik.uni-hamburg.de

- [http://pablobarros.net](http://pablobarros.net)
- [Uni Hamburg Webpage](https://www.inf.uni-hamburg.de/en/inst/ab/wtm/people/barros.html)
- [Google Scholar](https://scholar.google.com/citations?user=LU9tpkMAAAAJ)