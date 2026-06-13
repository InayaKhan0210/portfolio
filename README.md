# Personal Portfolio Website

A responsive personal portfolio website built to showcase my technical skills, projects, certifications, and journey in DevOps, Cloud Computing, and Platform Engineering.

## About

This portfolio serves as a central place to highlight my projects, technical experience, leadership activities, and learning path as an Electronics & Computer Engineering student with a strong interest in DevOps and cloud-native technologies.

The website is containerized using Docker and deployed on AWS EC2 to gain hands-on experience with modern deployment workflows and cloud infrastructure.

## Features

* Responsive and modern user interface
* Project showcase section
* Technical skills overview
* Education and certifications
* Leadership and extracurricular activities
* Contact information and social links
* Dockerized deployment
* Cloud hosting on AWS EC2

## Technologies Used

### Frontend

* HTML5
* CSS3
* JavaScript

### DevOps & Cloud

* Docker
* AWS EC2
* Git
* GitHub

### Development Tools

* VS Code
* Linux

## Project Structure

```text
portfolio/
├── index.html
├── css/
├── js/
├── assets/
├── images/
├── Dockerfile
└── README.md
```

## Running Locally

Clone the repository:

```bash
git clone https://github.com/InayaKhan0210/portfolio.git
cd portfolio
```

Open `index.html` directly in your browser or use a local server.

## Running with Docker

Build the Docker image:

```bash
docker build -t portfolio .
```

Run the container:

```bash
docker run -d -p 8080:80 portfolio
```

Visit:

```text
http://localhost:8080
```

## Deployment

The application is containerized using Docker and deployed on AWS EC2.

Deployment workflow:

1. Push code to GitHub
2. Build Docker image
3. Deploy container on AWS EC2
4. Access portfolio through public server IP or domain

## Featured Projects

### CI/CD Pipeline using GitHub Actions

Implemented an automated CI/CD workflow for build and deployment automation.

### Dockerized Portfolio Website

Containerized portfolio application using Docker and deployed on AWS EC2.

### Study Planner Website

Built a productivity-focused web application with Docker-based deployment and AWS hosting.

### Cloud Infrastructure & Monitoring Setup

Automated deployment pipeline using GitHub Actions, Docker, Docker Hub, and AWS EC2.

### Cloud-Native Monitoring Application

Deploying Prometheus and Grafana on Kubernetes for monitoring and observability.

## Connect With Me

* LinkedIn: https://www.linkedin.com/in/inaya-khan-a7111a334/
* GitHub: https://github.com/InayaKhan0210
* Portfolio: https://inayakhan0210.github.io/portfolio/
* Email: inaya.khan1002@gmail.com

## Future Improvements

* Custom domain integration
* Kubernetes deployment
* Automated CI/CD for portfolio updates
* Infrastructure as Code using Terraform
* Enhanced monitoring and analytics

---

Built by Inaya Vasim Khan
