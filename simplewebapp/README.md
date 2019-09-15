
1. Create a new folder
2. Checkout the Project
3. run the docker build command
```
docker build .
```
4. start the container
```
docker run -d -p 8080:8080  <<image id>>

-d is to run the image as demon
-p expose the docker port to outside the network
```
4. to access the application
```
http://localhost:8080
```
