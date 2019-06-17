# docker-proxy

A utility that helps manage a Docker container running codekitchen's http-proxy on MacOS using Docker for Mac. For Linux support see my new project below. For more information about the proxy, see https://github.com/codekitchen/dinghy-http-proxy

## New Version

I've completely re-written this tool and have given it a new name!  Check it out here https://github.com/aj-may/dotdocker 👈

## Installation

To install the proxy, run the following command:

```
curl -sL https://raw.githubusercontent.com/aj-may/docker-proxy/master/install.sh | bash
```

NOTE: If you first `cd` into a directory within your path, you will be able to run this utility from any command line afterwards. Normally it's best to put this in `/usr/local/bin`.

## Usage

```
docker-proxy status      Prints the status of the docker proxy.
docker-proxy start       Starts the docker proxy.
docker-proxy stop        Stops the docker proxy.
docker-proxy restart     Restarts the docker proxy.
docker-proxy update      Pulls the latest image for the docker proxy container.
docker-proxy help        Show this message.
docker-proxy version     Print the version number.
```
