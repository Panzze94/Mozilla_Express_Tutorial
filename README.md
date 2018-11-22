Mozilla tutorial fpr Express.js

To build a Docker image from the Dockerfile, run the following command:

docker build -t locallibrary https://github.com/Panzze94/Mozilla_Express_Tutorial.git

To run the image in a Docker container, use the command:

docker run -p 49160:8080 -d locallibrary
