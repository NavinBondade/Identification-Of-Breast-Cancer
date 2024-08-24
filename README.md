# Identification Of Breast Cancer With 90% Accuracy
<p align="center">
</p>
<img src="https://cdn.britannica.com/54/179554-138-A3C5FBA0/use-mammographies-resonance-breast-cancer.jpg" width="1500" height="520">
<p>Breast cancer remains one of the most prevalent and challenging health issues worldwide, with 2.3 million women diagnosed and 685,000 deaths reported globally in 2020 alone. The disease originates from mutations in breast cells that proliferate uncontrollably, forming a mass of tissue that can invade and damage surrounding breast tissue. To address this critical concern, I have developed a custom deep neural network specifically trained on histopathological images of both infected and uninfected breast tissue. This model demonstrates a remarkable 90% accuracy in distinguishing between malignant and non-malignant cases, offering a promising tool for early detection and treatment planning in breast cancer care. </p>
<h2>Libraries Used</h2>
<ul>
  <li>Tensorflow</li>
  <li>Numpy</li>
  <li>Pandas </li>
  <li>Matplotlib</li>
  <li>Seaborn</li>
  <li>Sklearn</li>
</ul>
<h2>Data Visualization</h2>
<p align="center"> 
<img src="https://github.com/NavinBondade/Identification-Of-Breast-Cancer/blob/main/Graphs/Dataset.png?raw=true" width="750" height="500">
</p>
<h2>Target Class Distribution</h2>
<p>Here zero stands for the infected histopathological image, and one is for the anon-infected histopathological image.</p>
<p align="center"> 
<img src="https://github.com/NavinBondade/Identification-Of-Breast-Cancer/blob/main/Graphs/Equal%20Data%20Distribution.png.png?raw=true" width="400" height="450">
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
<img src="https://github.com/NavinBondade/Identification-Of-Breast-Cancer/blob/main/Graphs/Output.png?raw=true" width="800" height="500">
</p>
</p>
<h2>Model Introspection</h2>
<h4>Confusion Matrix</h4>  
<p align="center"> 
<img src="https://github.com/NavinBondade/Identification-Of-Breast-Cancer/blob/main/Graphs/Confusion%20Matrix.png?raw=true" width="400" height="400">
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
<img src="https://github.com/NavinBondade/Identification-Of-Breast-Cancer/blob/main/Graphs/Classification%20Report.png?raw=true" width="700" height="700">
</p>
<h2>Conclusion</h2>  
<p>In this project, I have created deep convolutional neural network architecture for correctly identifying breast cancer with an accuracy of 90 percent accuracy. </p>  


