## 1. Build the docker image
Initially, it is required to run the following command to build the docker image:
> **docker build . -t \<your username>/node-web-app**

## 2. Run the docker image
Next, run the docker image with the command below:
> **docker run -p \<your local machine port>:8080 -d <your username>/node-web-app**