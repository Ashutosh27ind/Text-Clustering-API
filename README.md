# Text-Clustering-API
Implementation of a text clustering algorithm using Kmeans clustering in order to derive quick insights from unstructured text.  
Deployment using Dcoker and Flask API.

## Docker Setup
0. Install [Docker](https://docs.docker.com/engine/installation/)
1. Run `git clone https://github.com/Ashutosh27ind/Text-Clustering-API`
2. Open docker terminal and navigate to `/path/to/Text-Clustering-API`
3. Run `docker build -t clustering-api .`
4. Run `docker run -p 8180:8180 clustering-api`
5. Access http://localhost:8180/apidocs/index.html from your browser [assuming you are on windows. Otherwise just use IP of docker machine]  

  
![alt text](https://github.com/Ashutosh27ind/Text-Clustering-API/blob/main/docs/Capture.PNG?raw=true)


