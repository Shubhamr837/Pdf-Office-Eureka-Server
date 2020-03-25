# Pdf-Office-Eureka-Server


Prior knowledge of following are needed to run the application .
1 . kubernetes 
2 . GCP or aws 
3 . continous integration 

This Container is to be deployed with two other container :-
https://github.com/Shubhamr837/Pdf-Office-Zuul-Proxy
https://github.com/Shubhamr837/Pdf-to-Word-Server

This application is made with java spring . It is used for discovery of a service by another service .

The application is Deployed in Kubernetes , the deployment and service file for kubernetes can be found in k8s folder .
The image url has be be configured in deployment file with cloud build or any other build proccess.
the image url in kubernetes file need to be updated accordingly with the build process.

Cloud Build of Google cloud platform is used for Continous integration .
