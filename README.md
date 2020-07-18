# k3s-iot-microservices-raspberrypi

This is repo is all about running an IOT-web application on Raspberrypi 4/3, with K3S (lightweight kubernetes by rancher), the applications which designed as microservices runs on k3s pods (may be in cluster or in single node) in rpi.   

## Getting Started

To get start - Need to have a basic knowledge on Docker, Kubernetes, Raspberrypi, Node-MCU (ESP-8266)

### Prerequisites

The things needed to install on Raspberrypi - before going to steps do `apt-get update` on Rpi

```
Install Docker on Raspberrypi 
* curl -sSL https://get.docker.com | sh
* sudo usermod -aG docker pi
```

```
Install K3S on Raspberry pi 
* curl -sfL https://get.k3s.io | sh -
```

### Test services on Local (Not ARM-platform)

Software installation needed on local not a docker installation.

* [Golang](https://golang.org/dl/) - Golang for backend service.
* [Mongodb](https://docs.mongodb.com/manual/installation/) - Database Mongodb.
* [Nodejs](https://nodejs.org/en/download/) - Nodejs for frontend.
* [Arduino](https://www.arduino.cc/en/main/software) - Download arduino for client fetch and post datas to backend server.

If so Docker nothing is needed to download on local setup (lap/pc).
* TBD (Add docker commands)


## Running the tests

TBD

## Github pipeline integration

TBD


## Deployment

```
Run build.sh if the Raspberrypi has installed the prerequisite 
* Docker  
* K3S - Server 
```


## Author

* **Mohammed Bilal** - *Initial work* - [MHDBS](https://github.com/mhdbs)


## License

This project is licensed under the Apache License - see the [LICENSE.md](LICENSE.md) file for details

