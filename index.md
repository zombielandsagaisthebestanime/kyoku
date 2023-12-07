<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Welcome to My Website!</title>
  <style>
  body {
    background-image: url('blu.jpg');
    background-size: cover;
    background-repeat: no-repeat;
    background-attachment: fixed;
    color: black; /* Set text color to black */
    font-family: 'Arial', sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
  }

  h1, h2, h3, p {
    max-width: 800px;
    margin: auto;
  }

  img {
    max-width: 100%;
    height: auto;
    display: block;
    margin: auto;
    margin-top: 20px;
    opacity: 0.8; 
  }

  iframe {
    width: 100%;
    height: 600px;
    border: 1px solid #ddd;
    background: transparent; /* Set iframe background to transparent */
  }

  section {
    padding: 20px;
  }
</style>

</head>
<body>

  <h1>Welcome to My Website!</h1>

  <p>Here I have included some pictures, which are a visual analysis of Chinese citizens’ comments to the zero-coivd policy.</p>

  <section>
    <h2>Explore topics:</h2>

    <h3>1. <a href="distancemap.html">Discover the Wonders of Distance</a></h3>
    <p>Dive into the captivating world of distance exploration!</p>
    <iframe src="distancemap.html" frameborder="0"></iframe>

    <h3>2. <a href="jikan.html">Uncover the Evolution of Topics Over Time</a></h3>
    <p>Witness how topics evolve and change with the passage of time.</p>
    <iframe src="jikan.html" frameborder="0"></iframe>
  </section>

  <section>
    <h2>Co-occurrence Network Visualization</h2>

    <p><a href="kyoki.html">This is a co-occurrence network of several thousand submissions from January to April 2021</a></p>
    <p>I used <a href="https://pyvis.readthedocs.io/en/latest/">pyvis</a> to draw this visualization.</p>
    <iframe src="kyoki.html" frameborder="0"></iframe>
  </section>

  <section>
    <h2>Preview the Visual Delights:</h2>

    <h3>Cluster Map</h3>
    <img src="cluster.png" alt="Cluster Map">

    <h3>Heatmap: Research Paper Titles on Factor Analysis</h3>
    <p>I gathered titles from approximately 1000 Japanese research papers related to factor analysis. Using BERTopic, I generated a heatmap illustrating the covariance matrix.</p>
    <img src="heatmap.png" alt="Heatmap">

    <h3>Successful Version and Japanese Translation (Machine-Translated, Excuse Imperfections)</h3>
    <img src="topiceng.png" alt="Topic Image (English)">
    <br><br><br><br><br><br><br>
    <img src="topicjap1.png" alt="Topic Image (Japanese)">
    <br><br><br><br><br>

    <h3>Note: The following example serves as a learning experience! This corpus contains stop words, numbers, and irrelevant vocabulary.</h3>
    <img src="false.png" alt="False Example">
  </section>

</body>
</html>

---




