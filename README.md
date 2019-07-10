# realm-startapp

A bare bones project using Realm Framework.

## Getting Started

These instructions will get you a copy of the realm framework's simple 'hello-world' web project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites



```
node 8
Python 3.7
Rust 1.34.0
```

### Installing

install realm_cli using pip

```
pip install realm_cli
```

And next, clone the project with any name say 'foo.'

```
realm-cli startapp foo

```
Now you can see project directory with name 'foo'.


 

## Deployment

run following command to start server locally.
```
cd foo
realm-cli debug

```
open 127.0.0.1:3000 to see programmer's anthem.

## Info

```realm.json``` mentions source directories as ```source_dirs``` for elm compilation and destination directory as ```static_dir```, further same source directories has to be mentioned in elm.json too.

Directory Structure in all elm source directories has to be same as that inside ```/src``` for rust files.

All  Backend rust files should be located in ```/src```. 


## Built With

* [realm](https://github.com/ackotech/realm/) - A web framework written in Rust and Elm.