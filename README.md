<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>SONAR Rock vs Mine Prediction</title>
</head>
<body>

  <h1>🔍 SONAR Rock vs Mine Prediction</h1>
  <p>
    A machine learning project that classifies sonar signals as either <strong>Rock</strong> or <strong>Mine</strong> using Logistic Regression. 
    Built using Python and scikit-learn.
  </p>

  <h2>📁 Dataset</h2>
  <ul>
    <li><strong>Source:</strong> UCI Machine Learning Repository</li>
    <li><strong>Samples:</strong> 208</li>
    <li><strong>Features:</strong> 60 numeric attributes</li>
    <li><strong>Labels:</strong> <code>M</code> (Mine), <code>R</code> (Rock)</li>
  </ul>

  <h2>🎯 Objective</h2>
  <p>
    To train and evaluate a binary classification model and create a predictive system for real-time sonar input.
  </p>

  <h2>🧪 Libraries Used</h2>
  <ul>
    <li>numpy</li>
    <li>pandas</li>
    <li>scikit-learn</li>
  </ul>

  <h2>🛠️ How to Run</h2>
  <ol>
    <li>Clone the repository:
      <pre><code>git clone https://github.com/cheeseburden/-sonar-rock-vs-mine-prediction</code></pre>
    </li>
    <li>Install dependencies:
      <pre><code>pip install numpy pandas scikit-learn</code></pre>
    </li>
    <li>Launch Jupyter Notebook:
      <pre><code>jupyter notebook main.ipynb</code></pre>
    </li>
  </ol>

  <h2>📊 Model Details</h2>
  <ul>
    <li><strong>Model:</strong> Logistic Regression</li>
    <li><strong>Train/Test Split:</strong> 90% / 10%</li>
    <li><strong>Training Accuracy:</strong> ~83%</li>
    <li><strong>Testing Accuracy:</strong> ~76%</li>
  </ul>

  <h2>🧠 Sample Prediction</h2>
  <pre><code>
input_data = (0.1150, 0.1163, ..., 0.0680)
model.predict(reshaped_input)  # Output: ['M']
  </code></pre>


  <h2>👤 Author</h2>
  <p><a href="https://github.com/cheeseburden">cheeseburden</a></p>

</body>
</html>
