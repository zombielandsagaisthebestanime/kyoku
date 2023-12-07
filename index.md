<style>
  body {
    background-image: url('blue.png');
    background-size: cover;
    background-repeat: no-repeat;
    background-attachment: fixed;
    color: #8B4513;
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
</style>

# Welcome to My Website!

Explore topics:

1. [Discover the Wonders of Distance](distancemap.html)
   - Dive into the captivating world of distance exploration!  
   <iframe src="distancemap.html" width="100%" height="600" frameborder="0" style="border:1px solid #ddd;"></iframe>

2. [Uncover the Evolution of Topics Over Time](jikan.html)
   - Witness how topics evolve and change with the passage of time.  
   <iframe src="jikan.html" width="100%" height="600" frameborder="0" style="border:1px solid #ddd;"></iframe>

# Co-occurrence Network Visualization

[This is a co-occurrence network of several thousand submissions from January to April 2021](kyoki.html)

I used [pyvis](https://pyvis.readthedocs.io/en/latest/) to draw this visualization.

<iframe src="kyoki.html" width="100%" height="720" frameborder="0" style="border:1px solid #ddd;"></iframe>


## Preview the Visual Delights:

### Cluster Map
![Cluster Map](cluster.png)

### Heatmap: Research Paper Titles on Factor Analysis

I gathered titles from approximately 1000 Japanese research papers related to factor analysis. Using BERTopic, I generated a heatmap illustrating the covariance matrix.

![Heatmap](heatmap.png)


### Successful Version and Japanese Translation (Machine-Translated, Excuse Imperfections)
![Topic Image (English)](topiceng.png) <br><br><br><br><br><br><br>
![Topic Image (Japanese)](topicjap1.png)<br><br><br><br><br>

### Note: The following example serves as a learning experience! This corpus contains stop words, numbers, and irrelevant vocabulary.
![False Example](false.png)


---




