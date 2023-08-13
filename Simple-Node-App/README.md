
# Simple Node App
A basic Node.js application using Express.js, designed to be run both locally and in a Docker container.

## Prerequisites
Node.js and npm <br/>
Docker if you want to run the application in a container.


## Getting Started

### Clone the repository:

```
git clone https://github.com/your-username/simple-node-app.git
cd simple-node-app
```

### Install dependencies:

```
npm install
```

### Build the Docker image:

```
docker build -t simple-node-app .
```

### Run the Docker container by performing port mapping :

```
docker run -p 8080:8080 simple-node-app
```

### The application will be accessible at http://localhost:8080
