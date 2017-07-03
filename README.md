### Example app description

- Vagrant CentOS 7 box + Docker containers deployed with Ansible
- 3rd party containers such as MySQL, Consul and Registrator
- Python / Flask containerized app
- App uses Consul as Service Discovery mechanism to discover MySQL database
- [Registrator](https://github.com/gliderlabs/registrator) automatically registers and deregisters services for any Docker container by inspecting containers as they come online

### How to run

```
vagrant up
```

### Test app

Once Vagrant is done we can connect to VM with `vagrant ssh` and we can `curl localhost:8080` to ensure app is running.
