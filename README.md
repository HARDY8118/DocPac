# DocPac

A collection of shell scripts which can be used for using docker images of softwares packages.

### Why

Docker containers are self contained and can be easily removed with all data (configs and caches).
This feature can be used to install software packages temporarily or in an isolated environment.

**NOTE:** The capabilities of the scripts are limited and can only be used for simple use cases.

### Use cases

- Need to use a software without having trouble of installing
- Simple usage of software without many modifications

## Requirements

- Docker should be properly installed and configured
- BASH shell

## Usage

1. Download the script required and add it to your **PATH**. Make any modifications if required.
2. Make it executable
```bash
chmod +x [Script Name]
```
3. Run the script as normal software

It will take some time installing the required image for first time (or later if image is not available).

### Available scripts

+ deno
+ go
+ jenkins
+ node
+ python

Feel free to add a new script and open a new Pull Request.