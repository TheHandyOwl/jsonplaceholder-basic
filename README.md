# jsonplaceholder-basic
Simple docker container for setting up a fake server 'jsonplaceholder'<br>

## Website
More information about jsonplaceholder:<br>
[https://jsonplaceholder.typicode.com/](https://jsonplaceholder.typicode.com/)<br>
[https://github.com/typicode/json-server](https://github.com/typicode/json-server)<br>

## Setup

### Clone the github repository
`git clone https://github.com/TheHandyOwl/jsonplaceholder-basic`<br>

### Main folder
`cd jsonplaceholder-basic`<br>

### Building the docker container
Let's build the container with the Dockerfile configuration.<br>
`docker build -t jsonplaceholder-basic .`<br>

### Up and running
You can use a random external port like 3001 to map the internal port 3000<br>
`docker run -d -p 3001:3000 jsonplaceholder-basic`<br>

### Checking process
You should see the container<br>
`docker ps`<br>

### Checking process
Party time at port 3001!<br>
[http://0.0.0.0:3001/](http://0.0.0.0:3001/)<br>
