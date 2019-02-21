---
marp:true
---




<!-- 
$theme: default 
page_number: true
footer: Master IoT -- Universidad Politécnica de Madrid
-->


Part II. Containers
===

>Jessica Díaz
>Luis Fernando de Mingo López


---

# Introduction


Hola 

___

# Virtualization

Technique that allows the emulation of some technological resource: a hardware platform, an operating system or other network resources.

**Virtual machine**: Virtualization of an execution environment for the execution of applications. Examples: JVM (Java Virtual Machine), CLR (Common Language Runtime) .NET

**Hardware virtualization**: Virtualization of a complete hardware in which an operating system can be executed as if it were executed on real HW. In a virtualized environment you have several operating systems:

- Host operating system (host)
- Guest operating system (guest)

---

## Vagrant

Vagrant is a tool for building and distributing development environments.

- Development environments managed by Vagrant can run on local virtualized platforms such as VirtualBox or VMware, in the cloud via AWS or OpenStack, or in containers such as with Docker or raw LXC.

- Vagrant provides the framework and configuration format to create and manage complete portable development environments. These development environments can live on your computer or in the cloud, and are portable between Windows, Mac OS X, and Linux.

___

```console
vagrant init hashicporp/precise64
vagrant up
```

### Vagrant CLI

___

# Containers

## Docker

```
docker ps
```

___

### Docker CLI

# Provisioning 



## Ansible



## Puppet
