<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Loan Default Prediction - ML Project</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #f9f9f9;
      color: #333;
      line-height: 1.6;
      margin: 40px auto;
      max-width: 900px;
      padding: 0 20px;
    }
    h1, h2, h3 {
      color: #004080;
    }
    code {
      background: #eee;
      padding: 2px 5px;
      border-radius: 4px;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 15px;
    }
    table, th, td {
      border: 1px solid #ccc;
      padding: 10px;
      text-align: center;
    }
    th {
      background-color: #f0f8ff;
    }
    .section {
      margin-bottom: 40px;
    }
    a {
      color: #004080;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    .footer {
      margin-top: 60px;
      font-size: 0.9em;
      color: #666;
    }
    .folder-structure {
      background-color: #f4f4f4;
      padding: 15px;
      font-family: monospace;
      white-space: pre;
      border-left: 4px solid #004080;
    }
  </style>
</head>
<body>

  <h1>🧠 Loan Default Prediction — Machine Learning Project</h1>

  <div class="section">
    <p>This project applies various machine learning models to predict <strong>loan default risk</strong> based on borrowers' financial data. The goal is to help financial institutions make better lending decisions using data-driven insights.</p>
  </div>

  <div class="section">
    <h2>📌 Problem Statement</h2>
    <p>Build a predictive model to classify loan applicants as <strong>default</strong> or <strong>non-default</strong> using real-world financial features. The focus is on accuracy, model evaluation, and feature importance.</p>
  </div>

  <div class="section">
    <h2>🔍 Objectives</h2>
    <ul>
      <li>Preprocess and clean a large dataset (220k+ entries)</li>
      <li>Handle missing values and encode categorical variables</li>
      <li>Train & evaluate models including Ridge, Lasso, Random Forest & Neural Network</li>
      <li>Compare models using MSE and accuracy to select the best performer</li>
    </ul>
  </div>

  <div class="section">
    <h2>🛠️ Tech Stack & Tools</h2>
    <ul>
      <li><strong>Languages/Libraries:</strong> Python, Pandas, NumPy, Scikit-learn, Matplotlib, TensorFlow/Keras</li>
      <li><strong>ML Models:</strong> Linear, Ridge, Lasso, Random Forest, Neural Network</li>
      <li><strong>Preprocessing:</strong> Label Encoding, Standard Scaling, Correlation Analysis</li>
    </ul>
  </div>

  <div class="section">
    <h2>⚙️ Key Steps</h2>
    <ol>
      <li><strong>Data Preprocessing:</strong> Null handling, feature scaling, encoding</li>
      <li><strong>Feature Selection:</strong> Correlation & feature importance analysis</li>
      <li><strong>Model Training:</strong> Hyperparameter tuning for Ridge, Lasso, RF, and NN</li>
      <li><strong>Evaluation:</strong> MSE for regression, Accuracy for classification</li>
    </ol>
  </div>

  <div class="section">
    <h2>📊 Model Evaluation</h2>
    <table>
      <tr>
        <th>Model</th>
        <th>Train MSE</th>
        <th>Test MSE</th>
        <th>Train Accuracy</th>
        <th>Test Accuracy</th>
      </tr>
      <tr>
        <td>Linear Regression</td>
        <td>0.06683</td>
        <td>0.06768</td>
        <td>N/A</td>
        <td>N/A</td>
      </tr>
      <tr>
        <td>Ridge Regression</td>
        <td>0.06683</td>
        <td>0.06768</td>
        <td>N/A</td>
        <td>N/A</td>
      </tr>
      <tr>
        <td>Lasso Regression</td>
        <td>0.06847</td>
        <td>0.06939</td>
        <td>N/A</td>
        <td>N/A</td>
      </tr>
      <tr>
        <td>Random Forest</td>
        <td>0.03867</td>
        <td>0.03984</td>
        <td>96.13%</td>
        <td>96.01%</td>
      </tr>
      <tr>
        <td><strong>Neural Network</strong></td>
        <td><strong>0.02748</strong></td>
        <td><strong>0.03160</strong></td>
        <td><strong>96.74%</strong></td>
        <td><strong>96.29%</strong></td>
      </tr>
    </table>
  </div>

  <div class="section">
    <h2>🏁 Final Outcome</h2>
    <p>The <strong>Neural Network</strong> achieved the best performance and is recommended as the final model for production deployment. It demonstrated the lowest error and highest classification accuracy.</p>
  </div>

  <div class="section">
    <h2>🚀 Future Enhancements</h2>
    <ul>
      <li>Add cross-validation and grid search for tuning</li>
      <li>Deploy model via Flask or Streamlit app</li>
      <li>Integrate real-world loan datasets (e.g., LendingClub)</li>
    </ul>
  </div>

  <div class="section">
    <h2>👨‍💻 Author</h2>
    <p><strong>Osama Sher</strong><br>
      <a href="mailto:sherosama23@gmail.com">sherosama23@gmail.com</a> |
      <a href="https://www.linkedin.com/">LinkedIn</a> (Add your link)</p>
  </div>

  <div class="footer">
    ⚠️ This project is for academic purposes only. The analysis is not intended for real-world financial decisions.
  </div>

</body>
</html>
