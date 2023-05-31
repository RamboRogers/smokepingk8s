# SmokePing on K8s

This is an example manifest file to deploy the [linuxserver/smokeping](https://fleet.linuxserver.io/image?name=linuxserver/smokeping) in Kubernetes.

## Table of Contents

- [SmokePing on K8s](#smokeping-on-k8s)
  - [Table of Contents](#table-of-contents)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Contributing](#contributing)
  - [License](#license)
  - [Resources](#resources)


## Prerequisites

You'll need a working kubernetes deployment with a storage provider functional and the associated kubectl command line tool.

## Installation

On a system configured with your kubernetes tools.

```
kubectl apply -f smokeping.yaml
```

## Usage

This will create a service called "smokeping" that you can expose via your ingress controller.


## Contributing

Provide guidelines for contributing to the project. This could include information on how to report issues, submit pull requests, or contribute to the development of the Kubernetes manifest file.

## License

GNU GPL V3

## Resources

[linuxserver/smokeping](https://fleet.linuxserver.io/image?name=linuxserver/smokeping)

