BITSTASHCORE Node
============

A BITSTASH full node for building applications and services with Node.js. A node is extensible and can be configured to run additional services.

## Install

```bash
npm install -g bitstashcore-node
bitstashcore-node start
```

## Configuration

BITSTASHCORE includes a Command Line Interface (CLI) for managing, configuring and interfacing with your BITSTASHCORE Node.

```bash
bitstashcore-node create -d <data-dir> mynode
cd mynode
bitstashcore-node install <service>
bitstashcore-node install https://github.com/yourname/helloworld
```

This will create a directory with configuration files for your node and install the necessary dependencies. For more information about (and developing) services, please see the [Service Documentation](docs/services.md).

## Add-on Services

There are several add-on services available to extend the functionality of BITSTASHCORE:

- [BITSTASH Insight API](https://github.com/BITSTASH/bitstash-api)
- [BITSTASH Explorer](https://github.com/BITSTASH/bitstash-explorer)

## Contributing



## License
