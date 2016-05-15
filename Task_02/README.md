##README - Hello Docker Command Line Application



####To run the Hello Docker CLI application from a Docker container:

**1. Make sure you have a functioning Docker setup by issuing this command:**
>**$ docker run hello-world**

The output should state the following:
"Hello from Docker.
This message shows that your installation appears to be working correctly."
...
...

If Docker is not working or if you have not yet installed Docker 
please visit the [Docker Quickstart Page](https://docs.docker.com/engine/quickstart/)


**2. Enter this command which builds the image and saves it under the name 'ubuntu/hello_docker'**
>**$ docker build -t ubuntu/hello_docker .**

Make sure you are in the directory containing the Dockerfile and the hello_docker script before launching the above command.

**3. Run this command which launches the CLI application within the Docker image**
>**$ docker run ubuntu/hello_docker**

The output should show:

'Hello, Docker'





If there are any questions as to how to run this application please email:
[Email Edwin](mailto:efernand.cs@gmail.com)