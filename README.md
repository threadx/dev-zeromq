# ZeroMQ Dev Environment     

This is an Ubuntu dev container for building ZeroMQ apps using GCC/g++ with c/c++ bindings. Mount your project folders then make and test within.

For logging or creating local queues for IPCs, use:

	/var/log/mp

Maintained by [ClknGo Apps](https://www.clkngo.com/products/apps/dev-zeromq/).


## Installed Compiler Tools

* g++
* make
* xutils-dev
* libtool
* automake

### Libraries

* libzip-dev
* libcurl4-openssl-dev
* libxml2-dev

#### Libraries Built from Master
* libsodium
* libzmq
* libczmq

### Other

* wget
* traceroute
* unzip	
* git
* vim

## Run Example (boot2docker)

```
$ sudo docker run -it -v /c/Users:/home clkngo/dev-zeromq
```

