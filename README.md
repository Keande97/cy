# CyberDrop Command Line Interface
> Unofficial Cyberdrop.me Command Line Interface Album Downloader 

## Setup locally
Perform these steps to make initial setup of your work environment:
  1. Install the [Node.js](https://nodejs.org), it comes with the [NPM](https://docs.npmjs.com/) package manager
  
## Installation
```bash
$ npm install -g cyberdrop-cli
```

### Options

```
-p, --parallel      Download album images in parallel (faster but prone to corruption)
-o, --output        Downloaded album destinetion ( " . " for current directory)
```

## Usage
By default album will be stored into your local Downloads folder

```bash
$ cyberdrop-cli d [options] <album link>
```

use ``-o <directory>`` to specify outpu destination. ``-o .`` to output downloaded album to current working directory. 

```bash
$ cyberdrop-cli d -o <destination folder> <album link>
```
