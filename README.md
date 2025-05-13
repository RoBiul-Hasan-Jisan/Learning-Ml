<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>NumPy Notes</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      margin: 20px;
      padding: 20px;
      color: #333;
      line-height: 1.6;
    }
    h1, h2 {
      color: #007acc;
    }
    .check {
      color: green;
      font-weight: bold;
    }
    .note {
      background-color: #fff;
      border-left: 6px solid #007acc;
      padding: 10px 20px;
      margin-bottom: 20px;
      box-shadow: 0 0 5px rgba(0,0,0,0.1);
    }
    table {
      width: 100%;
      border-collapse: collapse;
      background: #fff;
      box-shadow: 0 0 5px rgba(0,0,0,0.1);
    }
    th, td {
      padding: 12px;
      text-align: left;
      border-bottom: 1px solid #ddd;
    }
    th {
      background-color: #007acc;
      color: white;
    }
    .highlight {
      color: #007acc;
      font-weight: bold;
    }
  </style>
</head>
<body>

  <h1>📘 NumPy Quick Notes</h1>

  <div class="note">
    <p class="check">✅ <strong>1. What is NumPy? Why is it used?</strong></p>
    <p><span class="highlight">NumPy</span> (Numerical Python) is a Python library used for numerical and scientific computing.</p>
    <p>It provides:</p>
    <ul>
      <li>A powerful N-dimensional array object (<code>ndarray</code>)</li>
      <li>Tools for performing vectorized operations (fast element-wise operations)</li>
      <li>Efficient mathematical, statistical, and linear algebra functions</li>
    </ul>
    <p><strong>🔹 Why it's used:</strong></p>
    <ul>
      <li>Much faster than regular Python lists (thanks to C-based implementation)</li>
      <li>Essential for data science, machine learning, and simulations</li>
      <li>Used in libraries like pandas, TensorFlow, scikit-learn, etc.</li>
    </ul>
  </div>

  <div class="note">
    <p class="check">✅ <strong>2. Difference between a Python list and a NumPy array?</strong></p>
    <table>
      <thead>
        <tr>
          <th>Feature</th>
          <th>Python List</th>
          <th>NumPy Array</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Data Type</td>
          <td>Can hold multiple types</td>
          <td>Only one data type (homogeneous)</td>
        </tr>
        <tr>
          <td>Speed</td>
          <td>Slower</td>
          <td>Much faster (vectorized ops)</td>
        </tr>
        <tr>
          <td>Memory</td>
          <td>Uses more memory</td>
          <td>Memory-efficient</td>
        </tr>
        <tr>
          <td>Broadcasting</td>
          <td>Not supported</td>
          <td>Supported</td>
        </tr>
        <tr>
          <td>Mathematical Ops</td>
          <td>Manual loop needed</td>
          <td>Vectorized (direct arithmetic)</td>
        </tr>
      </tbody>
    </table>
  </div>

</body>
</html>
