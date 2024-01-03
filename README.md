<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>

<body>

  <h1>Recipes Recommendation</h1>

  <h2>Objective</h2>
  <p>Build a recommender system to generate recipe recommendations for users. The focus is on achieving low prediction latency despite dealing with voluminous data.</p>

  <h2>Challenges and Solutions</h2>
  <p>Real-life recommender systems require instant results. To address this:</p>
  <ul>
    <li>Advanced Algorithms: Leveraged advancements in recommender and deep learning algorithms to improve prediction latency.</li>
    <li>Use of Big Data Hardware: Although unable to use industry-scale hardware, sub-sampled the dataset to make efficient use of available resources.</li>
  </ul>

  <h2>Spark Platform and ML Models</h2>
  <p>Utilize the Spark platform for building ML models:</p>
  <ul>
    <li>ALS (Alternating Least Squares): Collaborative filtering algorithm for matrix factorization.</li>
    <li>K Nearest Neighbors (KNN): Optional for building a hybrid recommender system.</li>
  </ul>

  <h2>Important Note</h2>
  <p>Avoid running ML algorithms on the full-scale data to prevent excessive AWS credits usage. Sub-sample the data for efficient processing.</p>

  <h2>Implementation Steps</h2>
  <ol>
    <li>Download the provided data files.</li>
    <li>Load the data into Spark.</li>
    <li>Preprocess and recalculate features if needed.</li>
    <li>Implement ALS algorithm for collaborative filtering.</li>
    <li>(Optional) Implement KNN for a hybrid recommender system.</li>
  </ol>

  <h2>Caution</h2>
  <p>Exercise caution when using large-scale clusters to avoid unnecessary AWS credits consumption.</p>

</body>

</html>
