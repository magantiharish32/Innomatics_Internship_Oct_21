# Internship_Oct_21

Plant Disease Recognition Mobile Application Development using Deep Learning
 
              Prathamesh Laxman Kashid    Saurav Singh   Maganti Harish     Paul Dennis        Dipak Bhole
INNOMATICS RESEARCH LABS , HYDERABAD
Abstract - Plant diseases are one of the grand challenges that face agriculture on a global scale.Crop diseases account for one-third of crop output losses in the United States each year. Despite its relevance, crop disease diagnosis by optical inspection of plant leaf symptoms is difficult for farmers with limited resources. Therefore, there is an urgent need for markedly improved detection, monitoring, and prediction of crop diseases to reduce crop agriculture losses. Computer vision ,CNN and Transfer Learning  has tremendous promise for improving crop monitoring at scale in this context. This paper presents an mobile-based system to automate the plant leaf disease diagnosis process. For identifying 38 disease types, the created system leverages Convolutional Neural Networks (CNN) as the underlying deep learning engine.

Keywords – Image Processing, Neural Networks, Classification, Disease Detection, Feature Extraction.

 
I. INTRODUCTION
Agriculture is an important part of our country as about 70% of the population depends on the farming for their living. Many farmers attempt suicide as a result of losses in output, which is a severe problem . This issue can be controlled to some extent by using new technologies that will help farmers to improve the harvesting. We collected an imagery dataset containing 87000 images of plant leaves of  healthy and infected plants for training, validating, and testing the CNN model Farmers can photograph sick plant leaves using the user interface, which is built as an Android mobile app. The disease category is then displayed, along with the confidence %. This system is designed to provide farmers with a greater possibility to keep their land crops healthy and eliminate the use of wrong fertilizers that could stress the plants


System Requirements
a .Hardware Specification
1. Processor : Intel i3 7th gen 
2. RAM : 4 GB (min) 
3. ROM : 80 GB 
4. Monitor : Color monitor (16-bit color)
b. Software Requirements
1. Operating System : Windows / Linux 
2. Simulation Tool : Jupyter Notebook or Googlecolab are two simulation tools.
c. Libraries Involved:

1.TensorFlow
2.Keras
3.Scikit Learn
4.Pickle
5.OpenCV



II. METHODOLOGY
 This system would create a better opportunity for farmers to keep their Keep your crops healthy by avoiding the use of harmful fertilisers that might stress your plants .Finally, we assessed our system's performance using a variety of measures such as classification accuracy and processing time . In recognising the most prevalent 38 disease types in crops, we discovered that our algorithm achieves an overall classification accuracy of 96 percent.
 
Fig.1.Data flow Diagram for disease classification from plants image using deep learning

 
Fig1a. Steps for the Plant Disease Detection


III.Module description
3.1 gathering of information
 
Fig.2.collection of data
3.2 Import libraries
  
Fig.3.Import libraries
3.3 Apply deep learning algorithm
deep learning method is very efficient, where experts used to take decades of It takes time to evaluate the toxicity of a certain structure, but with a deep learning model, toxicity may be determined in a fraction of the time (depends on complexity could be hours or days.Deep learning models are able to represent abstract concepts of the input in the multilevel distributed hierarchy. It enables multitask learning for all toxic effects just in one compact neural network, which makes it highly informative.
IV.Implementation and Testing

4.1 IMAGE PROCESSING:
Picture processing is a technique for applying operations on an image in order to improve it or extract relevant information from it. It is a type of signal processing in which input is an image and output may be image or characteristics/features associated with that image. 
4.2  PRE-PROCESSING OF DATA :  
 The data that is collected may be of different sizes.so the pre-processing of the data is necessary for the normalization of the data and to increase the efficiency of the model. For further pre-processing of the data, we use Data Generator function which is imported from the Tensorflow.
4.3 Image Acquisition:
Images are acquired with the help of a digital camera .The images are in the RGB format.. Color transformation structure is - applied for RGB images of the plants in different techniques

 
4.4 COLOR IMAGE PROCESSING
Color image processing is the analysis, transformation, and interpretation of visual data presented in color. It can provide a variety of outputs, ranging from a grayscale conversion of a black and white image to a comprehensive study of information contained in a telescope photograph. 
4.5 IMAGE ENHANCEMENT
Image enhancement refers to the process of highlighting certain information of an image, as well as weakening or removing any unnecessary information according to specific needs
 
4.6 IMAGE RESTORATION
Restoration attempts to reconstruct or recover an image that has been degraded by using a clear knowledge of the degrading phenomenon.



V. RESULTS & DISCUSSIONS
 
Fig1.conv2d_1_features layer visualization
 
Fig2.max_pooling2d_1_features layer visualization
 
Fig3.conv2d_2_features layer visualization

 
Fig4.max_pooling2d_2_features layer visualization


 
             Fig5. Final_Output

Training V/S Validation Accurracy
 
Fig6. Training V/S Validation Loss
Training V/S Validation Loss
 
Fig7. Training V/S Validation Loss

5.1 Advantages of the Proposed System:
It has achieved astonishing success in object detection and classification by combining large neural network models, called convolutional neural networks (CNNs)

VI. Application development  & CONCLUSION
A mobile application for detection and classification of Apple leaf disease using deep learning was developed in this study The proposed mobile application is designed to run as a standalone application on a smartphone. Experiments on Apple leaf images show that the application is able to achieve high accuracy on detecting Apple leaf diseases. Future work will extend the model to detect other types of crop diseases and will test the model on field environment.
 


REFERENCES
[1] S. Savary, A Ficke, JN. Aubertot, and C. Hollier, “Crop losses due to diseases and their implications for global food production losses and food security,” Food Security, vol. 4, no. 4, pp. 519-537, 2012. 
[2] C. Harvey, Z. Rakotobe, N. Rao, R. Dave, H. Razafimahatratra, and et al., “Extreme vulnerability of small holder farmers to agricultural risks and climate change in Madagascar,” Philosophical Trans. of the Royal Society B: Biological Sciences, vol. 369: 20130089, 2014.
 [3] J. Barbedo, “Digital image processing techniques for detecting, quantifying and classifying plant diseases,” SpringerPlus, vol. 2, article 660, pp. 1–12, 2013.
 [4] S. Mohanty, D. Hughes, and M. Salathe, “Using deep learning for image-based plant disease detection,” Frontiers in Plant Science, 7:1419 (doi: 10.3389/fpls.2016.01419), 2016. [5] A. Fuentes, S. Yoon, S. Kim, and D. Park, “A robust deep-learningbased detector for real-time tomato plant diseases and pests recognition,” Sensors, 17 (2022), 2017.
 [6] K. Ferentinos, “Deep learning models for plant disease detection and diagnosis,” Computers and Electronics in Agriculture, vol. 145, pp. 311–318, 2018. 
[7] E. Too, Y. Li, N. Sam, Y. Liu, “A comparative study of fine-tuning deep learning models for plant disease identification,” Computers and Electronics in Agriculture, vol. 161, pp. 272–279, 2019. 
[8] M.H. Saleem, J. Potgieter, and K.H. Arif, “Plant disease detection and classification by deep learning,” Plants, 8(11), 468 (doi:10.3390/ plants8110468), 2019. 
[9] M. Arsenovic, M. Karanovic, S. Sladojevic, A. Anderla, and D. Stefanovic, “Solving current limitations of deep learning based approaches for plant disease detection,” Symmetry, 11, 939 (doi:10.3390/sym11070939), 2019.
 [10] S. Strey, R. Strey, S. Burkert, P. Knake, K. Raetz, and et al., “Plantix – the mobile crop doctor,” Available online: https://plantix.net/ (accessed on 16 January 2020). 
[11] D. Hughes and et al., “PlantVillage,” Available online https://plantvillage.psu.edu/ (accessed on 16 January 2020).
 [12] W. Liu, D. Anguelov, D. Erhan, C. Szegedy, S. Reed, C. Fu, A. Berg, “SSD: Single Shot MultiBox Detector,” in Proceedings of the European Conference on Computer Vision—ECCV, Amsterdam, The Netherlands, October 2016.

