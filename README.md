# vagrant-docker-compose
Vagrant machine with docker and docker compose (1.24.1) pre-installed

# Run

To run this machine you must enable the Virtual Box Guest Plugin: 

```sh
vagrant plugin install vagrant-vbguest
```

Then just do 

```sh
vagrant up
vagrant ssh
```

# Update

```sh
vagrant up
vagrant package
vagrant cloud publish -r mauricext4fs/centos7-docker-compose <version> virtualbox package.box
```

