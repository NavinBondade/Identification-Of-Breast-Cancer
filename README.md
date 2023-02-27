# Identification Of Breast Cancer With 90% Accuracy
<p align="center">
</p>
<img src="https://cdn.britannica.com/54/179554-138-A3C5FBA0/use-mammographies-resonance-breast-cancer.jpg" width="1500" height="520">
<p>Breast cancer is one of the most common types of cancer. In 2020, there were 2.3 million women diagnosed with breast cancer and 685 000 deaths globally.  It occurs when breast cells mutate and grow out of control, creating a mass of tissue. Breast cancer can invade and grow into the tissue surrounding the breast. In this project, I have developed a custom deep neural network that has been trained on infected and uninfected breast cancer histopathological images and is able to identify whether a person has breast cancer or not with 90% accuracy. </p>
<h2>Libraries Used</h2>
<ul>
  <li>Tensorflow</li>
  <li>Numpy</li>
  <li>Pandas </li>
  <li>Matplotlib</li>
  <li>Seaborn</li>
  <li>Sklearn</li>
  <li>NLTK</li>
</ul>
<h2>Target Class Distribution</h2>
<p>Here zero stands for the infected histopathological image, and one is for the anon-infected histopathological image.</p>
<p align="center"> 
<img src="https://github.com/NavinBondade/Identification-Of-Breast-Cancer/blob/main/Graphs/Equal%20Data%20Distribution.png.png?raw=true">
</p>
<h2>Methodology and Approach</h2>
<p>Here, I have developed a neural network architecture that has been trained on six thousand positive and negative class breast cancer histopathological images. The model is made up of three CNN layers and three ANN layers. It has been trained for twenty epochs with binary cross entropy as the loss function and adam as the optimizer.</p>
<p align="center"> 
<img src="https://github.com/NavinBondade/Identification-Of-Breast-Cancer/blob/main/Graphs/model_graph.png?raw=true">
</p>
<h2>Model Training</h2>   
<h4>Model Loss:</h4>   
<p align="center"> 
<img src="https://github.com/NavinBondade/Identification-Of-Breast-Cancer/blob/main/Graphs/Loss.png?raw=true" width="700" height="400">
</p>
<h4>Model Accuracy:</h4>  
<p align="center"> 
<img src="https://github.com/NavinBondade/Identification-Of-Breast-Cancer/blob/main/Graphs/Accuracy.png?raw=true" width="700" height="400">
</p>
</p>
<h2>Model Evaluation</h2>
<ul>
  <li>Training Data Accuracy: 90 %</b></li>
  <li>Test Data Accuracy: 86 %</li>
  <li>Training Data Loss: 0.90</li> 
  <li>Test Data Loss: 0.31</li> 
</ul>  
<h2>Model Prediction</h2>
<p align="center"> 
<img src="https://github.com/NavinBondade/Identification-Of-Breast-Cancer/blob/main/Graphs/Output.png?raw=true" width="700" height="400">
</p>
</p>
<h2>Model Introspection</h2>
<h4>Confusion Matrix</h4>  
<p align="center"> 
<img src="https://github.com/NavinBondade/Identification-Of-Breast-Cancer/blob/main/Graphs/Confusion%20Matrix.png?raw=true" width="500" height="500">
</p>
<h4>Receiver Operating Characteristics (ROC)</h4>  
<p align="center"> 
<img src="https://github.com/NavinBondade/Identification-Of-Breast-Cancer/blob/main/Graphs/ROC.png?raw=true" width="700" height="400">
</p>
<h4>Precision vs. Recall curve</h4> 
<p align="center"> 
<img src="https://github.com/NavinBondade/Identification-Of-Breast-Cancer/blob/main/Graphs/Precision%20Vs%20Recall.png?raw=true" width="700" height="400">
</p>
<h4>Classification Report</h4>  
<p align="center"> 
<img src="" width="700" height="400">
</p>


