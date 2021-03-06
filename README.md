## Welcome to Elastic Stack Vagrant!

### First Steps
------

- Download **Vagrant** : [Link](https://www.vagrantup.com/downloads.html)

- Download **Virtualbox**: [Link](https://www.virtualbox.org/wiki/Downloads)

### Up and SSH
------

Download repository and run **Vagrant**. Example:

```bash
vagrant up
```

If everything was fine, login via **SSH** (password: vagrant):

```bash
vagrant ssh
```

Moreover, there are two kinds of network, **internal** and **public**. You can use **public network** in order to login via any kind of **ssh client** ([Putty](https://www.putty.org/), [MobaXterm](https://mobaxterm.mobatek.net/), [Termius](https://www.termius.com/)).

### Versions
------

| Product       | Version |
| ------------- | ------- |
| Elasticsearch | 7.12.0  |
| Kibana        | 7.12.0  |
| Logstash      | 7.12.0  |
| Beats         | 7.12.0  |

### Vagrant Commands
------

```bash
vagrant up : start vm
vagrant ssh : connect to vm
vagrant halt : shutdown vm
vagrant provision : apply shell script
```
