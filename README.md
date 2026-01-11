# Jetson Hub

This website will be used as a hub for my projects using the NVIDIA Jetson Orin Nano Developer Kit.
There will be demos, illustrations, explanations, and open source code for each project.

This project provides a Dockerized web interface to visualize a 3D model of the NVIDIA Jetson module. It serves a glTF rendering of the hardware via a static HTML page.

### Live Demo

You can view the live version of the project here:
[https://jetson.alexeber.fr](https://jetson.alexeber.fr)

### Getting Started

This project is configured to run with Docker and Docker Compose.

**Prerequisites**

* Docker
* Docker Compose

**Installation and Usage**

1. Navigate to the project directory.
2. Build and start the container using the following command:
```bash
docker-compose up -d --build
```

### Assets

The repository includes the source 3D files:

* **glTF/Bin:** Optimized files used for the web viewer.
* **STP:** The original CAD envelope file.
