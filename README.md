# Parazip
## Introduction

Parallel (multi-threaded) tar.bz2 archiving of a directory with lowest priority CPU and I/O scheduling. Utilizes all cpu cores and detaches into background, will syslog when it's done. Will install missing dependancies on RHEL based operating systems.

## Dependencies on CentOS/RHEL/Fedora

* util-linux
* coreutils
* pbzip2

## Installation

* Download from [Chotaire Git](https://git.chotaire.net/chotaire/parazip/releases) - [Github](https://github.com/chotaire/parazip/releases)
* tar -zxvf parazip.tar.bz2
* mv parazip.sh /usr/local/bin/parazip

## Usage

### Install Dependencies

`parazip install`

Will check for dependencies and install if not available.

### Run Parazip

`parazip <dir>`

Where \<dir\> is a directory name found in the current directory.


