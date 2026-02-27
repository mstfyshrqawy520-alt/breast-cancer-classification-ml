<h1 align="center">🩺 Breast Cancer Classification System</h1>
<h3 align="center">Machine Learning Based Medical Diagnosis</h3>

<hr/>

<h2>🚀 Project Overview</h2>
<p>
This project presents a complete Machine Learning pipeline for breast cancer diagnosis 
using the Wisconsin Diagnostic Breast Cancer (WDBC) dataset.
</p>

<p>
Multiple classification models were implemented and evaluated to distinguish between 
<b>Benign (B)</b> and <b>Malignant (M)</b> tumors based on nuclear cell features extracted 
from digitized images of fine-needle aspirates.
</p>

<hr/>

<h2>📊 Dataset Information</h2>

<p>
Dataset: Wisconsin Diagnostic Breast Cancer (WDBC)  
Number of instances: <b>569</b>  
Features: <b>30 real-valued input features</b>  
Classes:
<ul>
<li>357 Benign</li>
<li>212 Malignant</li>
</ul>
</p>

<p>
The dataset is publicly available on Kaggle:
</p>

<p>
<a href="https://www.kaggle.com/datasets/nancyalaswad90/breast-cancer-dataset">
Breast Cancer Dataset (Kaggle)
</a>
</p>

<p>
Dataset description reference: :contentReference[oaicite:0]{index=0}
</p>

<hr/>

<h2>🧠 Models Implemented</h2>

<table border="1" cellpadding="10">
<tr>
<th>Model</th>
<th>Accuracy</th>
</tr>
<tr>
<td>SVC</td>
<td><b>0.9737</b></td>
</tr>
<tr>
<td>Decision Tree</td>
<td>0.9386</td>
</tr>
<tr>
<td>Random Forest</td>
<td>0.9386</td>
</tr>
<tr>
<td>Extreme Gradient Boosting</td>
<td>0.9386</td>
</tr>
</table>

<p>
Class balancing improved performance compared to training without balancing.
</p>

<p>
Model performance source: :contentReference[oaicite:1]{index=1}
</p>

<hr/>

<h2>⚙️ Machine Learning Pipeline</h2>
<ul>
<li>Data Cleaning</li>
<li>Feature Scaling</li>
<li>Class Balancing</li>
<li>Model Training</li>
<li>Model Comparison</li>
<li>Performance Evaluation</li>
</ul>

<hr/>

<h2>📈 Evaluation Metrics</h2>
<ul>
<li>Accuracy</li>
<li>Precision</li>
<li>Recall</li>
<li>Confusion Matrix</li>
</ul>

<hr/>

<h2>📂 Project Structure</h2>

<pre>
breast-cancer-classification-ml/
│
├── breast_ML.ipynb
├── dataset link.txt
├── DatasetDescription.txt
├── model_used.txt
├── README.md
└── requirements.txt
</pre>

<hr/>

<h2>⚙️ Installation</h2>

<pre>
git clone &lt;repository-link&gt;
cd breast-cancer-classification-ml
pip install -r requirements.txt
jupyter notebook
</pre>

<hr/>

<h2>🛠 Technology Stack</h2>
<ul>
<li>Python</li>
<li>Scikit-learn</li>
<li>Pandas</li>
<li>NumPy</li>
<li>Matplotlib</li>
<li>Seaborn</li>
</ul>

<hr/>

<h2>💡 Engineering Highlights</h2>
<ul>
<li>Comparative model evaluation</li>
<li>Medical dataset application</li>
<li>Class balancing techniques</li>
<li>Feature-based tumor diagnosis</li>
</ul>

<hr/>

<h3 align="center">👨‍💻 Developed by Mostafa Sharqawy</h3>
<p align="center">AI Engineer | Machine Learning | Medical AI</p>
