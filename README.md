# ZMQ demo (C)

Esta carpeta contiene programas de ejemplo de la biblioteca `czmq` (ZeroMQ para C). Note que `czmq` corresponde a un API de alto nivel para `libzmq`.

## Pasos de construcción
Desde el contenedor de desarrollo instale las bibliotecas `libzmq` y `czmq` utilizando CMake:

```console
$ git clone https://github.com/zeromq/libzmq.git
$ cd libzmq
$ mkdir build
$ cd build
$ cmake ..
$ sudo make install
$ sudo ldconfig
```

```console
$ git clone https://github.com/zeromq/czmq.git
$ cd czmq
$ mkdir build
$ cd build
$ cmake ..
$ sudo make install
$ sudo ldconfig
```

Desde el contenedor de desarrollo en el directorio base del ejemplo (`examples/c/zmq_demo/`) ejecute los siguiente comandos:

```console
$ mkdir build
$ cd build
$ cmake ..
$ make
```

