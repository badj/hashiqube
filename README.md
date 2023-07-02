# Hashiqube Overview
Hashiqube is a Docker Container (Default) or a VM (Virtualbox). Hashiqube has a Docker daemon inside. It runs all Hashicorp products. __Vault, Terraform, Nomad, Consul, Waypoint, Boundary, Vagrant, Packer and Sentinel.__
It also runs a host of other popular Open Source DevOps / DevSecOps applications (Minikube, Ansible AWX Tower, Traefik etc.) showcasing how simple integration with Hashicorp products can result in tangible learnings and benefits for all its users.

Once Hashiqube is up an internet connection is no longer needed meaning sales pitches and demos for potential and existing customers is greatly aided.

Hashiqube was created by Riaan Nolan, to help him learn about Hashicorp's suite of fantastic software, and Hashiqube can help you too! Good luck on your learning pathway! 

You are welcome to connect with Riaan Nolan on Linkedin https://www.linkedin.com/in/riaannolan/ <br />
Riaan Nolan's Credly profile: https://www.credly.com/users/riaan-nolan.e657145c

## Pre-requisites
* 10GB of disk space
* Admin rights / sudo
* Docker (Default) or Virtualbox
* Vagrant
* `vagrant up --provision`

## Instructions
:clock3: Duration 15 - 30 minutes <br>
:bulb: Docker is the Default and preferred way to run Hashiqube

* Docker - Download __Docker__ from https://www.docker.com/products/docker-desktop and install
* Vagrant - Download __Vagrant__ from https://www.vagrantup.com/downloads.html and install
* Virtualbox (Optional) - Download __Virtualbox__ from https://www.virtualbox.org/wiki/Downloads and install
* Using `git` - clone this repo `git clone $repo .` [__What is Git?__](git/#git)
* Inside the local repo folder, do `vagrant up --provision` - This will setup, Vault, Nomad, Consul, Terraform, Localstack and Docker
* Documentation locally available at http://localhost:3333

## Hashiqube Diagrams

In essence Hashiqube is a Docker Container (by default) or a Virtual Machine.

Hashiqube has a Docker Daemon inside. And it runs on your local laptop or a cloud instance.

Hashiqube runs all the Hashicorp products and other popular Open Source tools, such as Minikube, Ansible AWX Tower, Prometheus and Grafana and many, many more, See [__Hashiqube Integrations__](/?id=hashiqube-integrations-1)

You can also run Hashiqube on AWS, GCP and Azure. This is called Hashiqube Multi-Cloud, see: [__Multi-Cloud__](multi-cloud/README)

Hashiqube is a Training / Development Lab for you to practise, learn or demo POC stuff with, it should not be run in production.

It can be visualized with below diagram.

![HashiQube Diagram](images/hashiqube-diagram.png?raw=true "HashiQube Diagram")

## Links
Hashicorp blog post: https://www.hashicorp.com/resources/hashiqube-a-development-lab-using-all-the-hashicorp-products <br />
Hashiqube Website: https://hashiqube.com <br />
Hashiqube Github: https://github.com/star3am/hashiqube <br />
Hashiqube Youtube: https://www.youtube.com/watch?v=6jGDAGWaFiw <br />
Hashiqube Medium: https://medium.com/search?q=hashiqube <br />
Hashiqube Terraform Registry module: https://registry.terraform.io/modules/star3am/hashiqube/hashicorp/latest <br />

## Hashiqube Integrations
![HashiQube](images/thestack.png?raw=true "HashiQube")

* [__Multi Cloud__](multi-cloud/#terraform-hashicorp-hashiqube) - Hashiqube on AWS, GCP and Azure (Clustered) https://registry.terraform.io/modules/star3am/hashiqube/hashicorp/latest
* [__Vagrant__](hashicorp/#vagrant) - Vagrant is an open-source software product for building and maintaining portable virtual software development environments; e.g., for VirtualBox, KVM, Hyper-V, Docker containers, VMware, and AWS. It tries to simplify the software configuration management of virtualization in order to increase development productivity
* [__Vault__](hashicorp/#vault) - Secure, store and tightly control access to tokens, passwords, certificates, encryption keys for protecting secrets and other sensitive data using a UI, CLI, or HTTP API.
* [__Consul__](hashicorp/#consul) - Consul uses service identities and traditional networking practices to help organizations securely connect applications running in any environment.
* [__Nomad__](hashicorp/#nomad) - A simple and flexible scheduler and orchestrator to deploy and manage containers and non-containerized applications across on-prem and clouds at scale.
* [__Traefik__](hashicorp/#traefik-load-balancer-for-nomad) - Traefik is a modern HTTP reverse proxy and load balancer that seamlessly integrates with Nomad
* [__Fabio__](hashicorp/#fabio-load-balancer-for-nomad) - Fabio is an HTTP and TCP reverse proxy that configures itself with data from Consul
* [__Terraform__](hashicorp/#terraform) - Use Infrastructure as Code to provision and manage any cloud, infrastructure, or service
* [__Packer__](hashicorp/#packer) - Create identical machine images for multiple platforms from a single source configuration.
* [__Sentinel__](hashicorp/#sentinel) - Sentinel is an embedded policy-as-code framework
* [__Waypoint__](hashicorp/#waypoint) - Waypoint is an open source solution that provides a modern workflow for build, deploy, and release across platforms
* [__Boundary__](hashicorp/#boundary) - Simple and secure remote access to any system from anywhere based on user identity.
* [__Docker__](docker/#docker) - Securely build, share and run any application, anywhere
* [__Localstack__](localstack/#localstack) - A fully functional local AWS cloud stack
* [__Ansible__](ansible/#ansible) - Ansible is a suite of software tools that enables infrastructure as code. It is open-source and the suite includes software provisioning, configuration management, and application deployment functionality.
* [__LDAP__](ldap/#ldap) - Lightweight Directory Access Protocol
* [__Jenkins__](jenkins/#jenkins) - Jenkins is an open source automation server. It helps automate the parts of software development related to building, testing, and deploying, facilitating continuous integration and continuous delivery. 
* [__Oracle MySQL__](database/#oracle-mysql) - MySQL is an open-source relational database management system (RDBMS)
* [__Microsoft MSSQL__](database/#microsoft-sql-mssql-express) - Microsoft SQL Server is a relational database management system developed by Microsoft
* [__PostgreSQL__](database/#postgresql) - PostgreSQL, also known as Postgres, is a free and open-source relational database management system emphasizing extensibility and SQL compliance.
* [__Minikube__](minikube/#minikube) - Minikube implements a local Kubernetes cluster on macOS, Linux, and Windows.
* [__Newrelic Kubernetes Monitoring__](newrelic-kubernetes-monitoring/#newrelic-kubernetes-monitoring) - Monitor Kubernetes Clusters and Workloads with Newrelic
* [__Docsify__](docsify/#docsify) - A magical documentation site generator
* [__Mermaid__](mermaid/#mermaid) - Generation of diagram and flowchart from text in a similar manner as markdown
* [__Prometheus__](prometheus-grafana/#prometheus-and-grafana) - Open-source monitoring system with dimensional data model, flexible query language, efficient time series database & modern alerting
* [__Grafana__](prometheus-grafana/#prometheus-and-grafana) - Grafana is the open source analytics & monitoring solution for every database
* [__Elasticsearch__](elasticsearch-kibana-cerebro/#elasticsearch-kibana-and-cerebro) - Elasticsearch is a search engine based on the Lucene library
* [__Kibana__](elasticsearch-kibana-cerebro/#elasticsearch-kibana-and-cerebro) - Kibana is an open source data visualization dashboard for Elasticsearch
* [__Cerebro__](elasticsearch-kibana-cerebro/#elasticsearch-kibana-and-cerebro) - Cerebro is the evolution of the previous Elasticsearch plugin Elasticsearch kopf
* [__Ansible-Tower__](ansible-tower/#ansible-tower) - Is a web-based solution that makes Ansible even more easy to use for IT teams of all kinds. It’s designed to be the hub for all of your automation tasks.
* [__Dbt__](dbt/#dbt) - Dbt is a data transformation tool that enables data analysts and engineers to transform, test and document data in the cloud data warehouse
* [__Airflow__](apache-airflow/#apache-airflow) - Apache Airflow is an open-source workflow management platform for data engineering pipelines
* [__Visual-Studio-Code__](visual-studio-code/#visual-studio-code) - Visual Studio Code is a code editor redefined and optimized for building and debugging modern web and cloud applications
* [__Portainer__](portainer/#portainer) - A lightweight service delivery platform for containerized applications that can be used to manage Docker, Swarm, Kubernetes and ACI environments. It is designed to be as simple to deploy as it is to use.
* [__Gitlab__](gitlab/#gitlab) - GitLab is a complete DevOps platform, delivered as a single application

Once the stack is up you will have a large number of services running and available on `localhost` <br />
For Documentation please open http://localhost:3333 in your browser

![Hashiqube Integrations](images/logo-qube.png?raw=true "Hashiqube Integrations")

## Purpose
Hashiqube has been created to enable anyone who is interested in secure automation pipelines the ability to run a suite of ‘best in class’ tools their local machines at the cost of a small amount of system resources.

Hashiqube gives all interested parties the empowerment to  deploy these tools in a way covers multiple use cases effectively providing a ‘concept to completion’ test bed using open source Hashicorp products.

The original use case was born the desire to demystify DevSecOps utilising Terraform, Vault, Consul, Sentinel and Nomad as well as some other well know open source CI/CD tools by providing a ‘hands-on’ environment that demonstrates the value of secret and credential management in a standard software development pipeline.

Thanks to the flexibility of the Hashicorp products there is no need to wonder how to achieve the goals of bringing software to market in a more secure and timely fashion, just Vagrant up!

## Supported Architectures
| Name | Docker | Virtualbox | Hyper-V
|------|--------|------------|---------|
| amd64 | ✓ | ✓ | ✘ |
| arm64 | ✓ | ✘ | ✘ |
| linux | ✓ | ✓ | ✘ |
| windows | ✓ | ✘ | ✘ |
| mac intel | ✓ | ✓ | ✘ |
| mac apple | ✓ | ✘ | ✘ |

## Components
Hashiqube is made up out of a number of components and some rely on each other. 

For example you can run components seperately as demonstrated below.
```bash
vagrant up --provision-with basetools
vagrant up --provision-with docker
vagrant up --provision-with docsify
vagrant up --provision-with vault
vagrant up --provision-with nomad
vagrant up --provision-with minikube
```

Or one-shot as demonstrated below.
```bash
vagrant up --provision-with basetools,docker,minikube,postgresql,dbt,apache-airflow
```

#### Docker Desktop
Docker Desktop is an easy-to-install application for your Mac or Windows environment that enables you to build and share containerized applications and microservices. It's a graphical user interface for the docker service.

* Download __Docker Desktop__ from https://www.docker.com/products/docker-desktop and install it on your laptop, to verify bring up the Docker Desktop application. 

If you have HashiQube running, you won't see any containers but you will be able to open the application. 

![Docker Desktop](images/docker_desktop_installed.png?raw=true "Docker Desktop")

Now that docker is installed we need to ensure that the docker environment and settings are configured

- Ensure you have the latest version installed
- Ensure that your Operating System is updated see: https://www.docker.com/blog/speed-boost-achievement-unlocked-on-docker-desktop-4-6-for-mac/

##### Docker Desktop Resources

:bulb: You can quite happily run Hashiqube with 8G of RAM, but once you start running, Vault, Nomad, Consul, Waypoint, Boundary AND you want to run Minikube with let's say AWX Ansible Tower, the processes will start contending for resources and you will get weird errors. For that reason, below screenshot is my setup with 12G of RAM. For reference I use an M1 Macbook Air with 16G or RAM as my personal laptop.

![Docker Desktop Resources](images/docker_installed_resources.png?raw=true "Docker Desktop Resources")

* Ensure that you give your docker daemon at least __8G of RAM__ and sufficient disk space

## Consul DNS
__Local DNS via Consul__ <br />
Add on our local Macbook a file __/etc/resolver/consul__ with below contents
```
nameserver 10.9.99.10
port 8600
```
Now you can use DNS like nomad.service.consul:9999 vault.service.consul:9999 via Fabio Load Balancer <br />

## The HashiStack
| Dimension | Products | | | 
|------|--------|------------|------------|
| __Applications__ | ![Nomad](https://www.datocms-assets.com/2885/1620155098-brandhcnomadprimaryattributedcolor.svg) <br /> [__Nomad__](hashicorp/#nomad) <br /> Schedular and workload orchestrator to deploy and manage applications | ![Waypoint](https://www.datocms-assets.com/2885/1620155130-brandhcwaypointprimaryattributedcolor.svg) <br /> [__Waypoint__](hashicorp/#waypoint) <br /> One workflow to build, deploy and release applications across platforms| | 
| __Networking__ | ![Consul](https://www.datocms-assets.com/2885/1620155090-brandhcconsulprimaryattributedcolor.svg) <br /> [__Consul__](hashicorp/#consul) <br /> Service Mesh across any cloud and runtime platform | | |
| __Security__ | ![Boundary](https://www.datocms-assets.com/2885/1620155080-brandhcboundaryprimaryattributedcolor.svg) <br /> [__Boundary__](hashicorp/#boundary) <br /> Secure remote access to applications and critical systems | ![Vault](https://www.datocms-assets.com/2885/1620159869-brandvaultprimaryattributedcolor.svg) <br /> [__Vault__](hashicorp/#vault) <br /> Secure management of secrets and sensitive data| |
| __Infrastructure__ | ![Packer](https://www.datocms-assets.com/2885/1620155103-brandhcpackerprimaryattributedcolor.svg) <br /> [__Packer__](hashicorp/#packer) <br /> Automated machine images from a single source configuration| ![Vagrant](https://www.datocms-assets.com/2885/1620155118-brandhcvagrantprimaryattributedcolor.svg) <br /> [__Vagrant__](hashicorp/#vagrant) <br /> Single workflow to build and manage developer environments| ![Terraform](https://www.datocms-assets.com/2885/1620155113-brandhcterraformprimaryattributedcolor.svg) <br /> [__Terraform__](hashicorp/#terraform) <br /> Infrastructure automation to provision and manage any cloud service |

## Other
* LDAP can be accessed on ldap://localhost:389
* Localstack web http://localhost:8080
* DBT web http://localhost:28080
* Apache Airflow http://localhost:18889
* Ansible provisioning Apache2 http://localhost:8888
* Ansible AWX Tower http://localhost:8043
* Jenkins http://localhost:8088
* Oracle MySQL localhost:3306
* Microsoft SQL localhost:1433
* Minikube http://localhost:10888
* Traefik http://localhost:8181
* Fabio http://localhost:9999

### Vagrant Basic Usage
* vagrant up --provision OR vagrant up --provision-with bootstrap|nomad|consul|vault|docker|ldap
* vagrant global-status # to see which VMs are active
* vagrant global-status --prune # to remove stale VMs from Vagrant cache
* vagrant status # vagrant status
* vagrant reload
* vagrant up
* vagrant destroy
* vagrant provision
* vagrant plugin list

### Docker Basic Usage
* docker image ls
* docker ps
* docker stop

### Errors you might encounter
:bulb: If you see this error message

```
The IP address configured for the host-only network is not within the
allowed ranges. Please update the address used to be within the allowed
ranges and run the command again.

Address: 10.9.99.10
Ranges: 192.168.56.0/21

Valid ranges can be modified in the /etc/vbox/networks.conf file. For
more information including valid format see:

https://www.virtualbox.org/manual/ch06.html#network_hostonly
```

Please create the following file: __/etc/vbox/networks.conf__ with the following contents

```
* 10.0.0.0/8 192.168.0.0/16
* 2001::/64
``` 

and re-run `vagrant up --provision`

__Error__ response from daemon: cannot stop container: 6c0c8135620ff47efe12df417a0df0e57d7a81a7f7ca06d011323fbb52e573db: tried to kill container, but did not receive an exit event <br />
__Command__ `vagrant destroy` <br />
__Solution__ run `vagrant destroy` again <br />
```
    hashiqube0.service.consul: Are you sure you want to destroy the 'hashiqube0.service.consul' VM? [y/N] y
==> hashiqube0.service.consul: Stopping container...
A Docker command executed by Vagrant didn't complete successfully!
The command run along with the output from the command is shown
below.

Command: ["docker", "stop", "-t", "1", "6c0c8135620ff47efe12df417a0df0e57d7a81a7f7ca06d011323fbb52e573db", {:notify=>[:stdout, :stderr]}]

Stderr: Error response from daemon: cannot stop container: 6c0c8135620ff47efe12df417a0df0e57d7a81a7f7ca06d011323fbb52e573db: tried to kill container, but did not receive an exit event
```

__Error__ The IP address configured for the host-only network is not within the allowed ranges. Please 
update the address used to be within the allowed ranges and run the command again. <br />
__Command__ `vagrant up --provision` <br /> 
__Solution__ Ensure the following contents are present in `/etc/vbox/networks.conf` <br>
```
* 10.0.0.0/8 192.168.0.0/16
* 2001::/64
```

## To investigate
### CI/CD
    Gatling: (load testing) https://gatling.io/open-source
    Spinnaker for multi-cloud / multi swim lane CD tool: https://www.spinnaker.io/concepts/
    Build agent showing code clean and dirty.
        Java
        Python
        JavaScript

### Monitoring / Dash-boarding
    Hygiea dashboard: https://github.com/Hygieia/Hygieia
    Alerting will be handled by a local docker messaging server such as Gotify: https://github.com/gotify/server

### Containerisation and API’s
    Gloo: https://docs.solo.io/gloo/latest/introduction/

## Support & Feedback
For suggestions, feedback and queries please branch or and submit a Pull Request or directly contact Riaan Nolan, creator of the HashiQube via Github: https://github.com/star3am/hashiqube

## About
Hashiqube has been created to help Engineers, Developers and anyone who wants to practise, learn or demo Hashicorp products to get started quickly with a local lab. 

### About Hashiqube
Hashiqube runs all the Hashicorp products and a host of other popular Open Source software taht is heavily used in the industry. 

Once you have done `vagrant up --provision` you will have access to Vault, Nomad, Consul, Boundary, Waypoint and this documnetation page on your local computer.

* Vault http://localhost:8200 `vagrant up --provision-with basetools,vault`
* Nomad http://localhost:4646 `vagrant up --provision-with basetools,docker,nomad`
* Consul http://localhost:8500 `vagrant up --provision-with basetools,consul`
* Waypoint on Nomad https://localhost:9702 `vagrant up --provision-with basetools,docker,waypoint`
* Waypoint on Minikube https://localhost:19702 `vagrant up --provision-with basetools,docker,waypoint-kubernetes-minikube`
* Boundary http://localhost:19200 `vagrant up --provision-with basetools,boundary`
* Docsify http://localhost:3333 `vagrant up --provision-with basetools,docsify`

In addition to the Core Hashicorp products, Hashiqube also runs a host of other popular Open Source integrations that are heavily used within the industry today. 

![Hashiqube Integrations](images/logo-qube.png?raw=true "Hashiqube Integrations")

### About Me
My name is Riaan Nolan and I was born in South Africa. I started out as a Web Developer in 2000 and from there progressed into Systems Administration, with a strong focus on Automation, Infrastrtucture and Configuration as Code.

I have worked for Multi-National companies in Portugal, Germany, China, South Africa, United States and Australia. 

You are welcome to connect with me on Linkedin https://www.linkedin.com/in/riaannolan/ <br />
Credly profile: https://www.credly.com/users/riaan-nolan.e657145c

![My Hashicorp Badges](images/hashicorp-badges.png?raw=true "My Hashicorp Badges")

## Contributors and Special mentions
A Very special mention to HashiQube's contributors, Thank You All for your help, suggestions and contributions no matter how small <3
 - Thomas Cockin
 - Konstantin Vanyushov
 - Tristan Morgan
 - Ringo Chan
 - Ehsan Mirzaei
 - Greg Luxford
 - Byron Tuckett
 - Lane Birmingham
 - Devang Dhameliya
 - Rajesh Cholleti
 - Nel-Marie Nolan
 - Adriana Villela

## Videos
Videos were made with asciinema https://asciinema.org/
- asciinema rec -i 1
- asciicast2gif -S 1 -s 2 tmpd1zpq13n-ascii.cast tmpd1zpq13n-ascii.gif

## License
HashiQube is available as open-source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

![Automate all the things](images/automate-all-the-things.png?raw=true "Automate all the things")