# NGINX Plus on Ubuntu
Ansible playbook to provision NGINX Plus in an Ubuntu 16.04 Vagrant box. Feel free to tinker and make it yours.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.
- Just clone this repository by typing: `git clone https://github.com/Lemmah/nginx-plus-ubuntu16.04.git`
- Switch to project directory: `cd nginx-plus-ubuntu16.04`
- The NGINX web server listens on port 80 in guest... Wait, you have to have some stuff before you get to this point. So these are:

### Prerequisites

- VirtualBox
- Vagrant


### Installing

- Install the prerequisites by going to their respective websites and following required steps for your specific OS.
- To start the vagrant box, `vagrant up`
- The NGINX webserver listens on port :80 in the guest which is forwarded to port :8086 in your host OS. Visit localhost:8086 to view the nginx web server.
- If you got here, you know what to do next! 😃 Enjoy!

## Authors

* **James Lemayian** - *Lead Contributor* - [@lemmah](https://github.com/lemmah)


## License

This project is currently under the [MIT Licencse](/LICENSE).

## Acknowledgments

* Andela Kenya - For the resources.
