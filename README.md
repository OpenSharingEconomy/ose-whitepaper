# Open Sharing Economy - Whitepaper

This repository contains all documents related to the description of the Open Sharing Economy Ecosystem (OSEE).

The whitepaper is currently in a early draft version.

This readme is targeted at the team itself.

## Developer guide

Texmaker is used, along with some LaTeX extensions. For this purpose, we need to install Texmaker and MiKTeX.

### Prerequisites

#### Linux

**1. Texmaker** (From http://www.xm1math.net/texmaker/)

```bash
sudo apt-get install texmaker -y
```

**2. MiKTeX** (From https://miktex.org/howto/install-miktex-un)

Ubuntu 18.04 (64-bit)

```bash
sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys D6BC243565B2087BC3F897C9277A7293F59E4889
echo "deb http://miktex.org/download/ubuntu bionic universe" | sudo tee /etc/apt/sources.list.d/miktex.list
sudo apt-get update
```

Ubuntu 16.04, Linux Mint 18 or higher (64-bit)

```bash
sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys D6BC243565B2087BC3F897C9277A7293F59E4889
echo "deb http://miktex.org/download/ubuntu xenial universe" | sudo tee /etc/apt/sources.list.d/miktex.list
sudo apt-get update
```

Debian 9 (64-bit)

```bash
sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys D6BC243565B2087BC3F897C9277A7293F59E4889
echo "deb http://miktex.org/download/debian stretch universe" | sudo tee /etc/apt/sources.list.d/miktex.list
sudo apt-get update
```

And then:

```bash
sudo apt-get install -y
miktexsetup finish
initexmf --set-config-value=[MPM]AutoInstall=yes
```

#### Windows 7-8-10

**1. Texmaker** 

Go to http://www.xm1math.net/texmaker/ and follow instructions

**2. MiKTeX** 

Go to https://miktex.org/howto/install-miktex-un and follow instructions


### Usage

In Texmaker: 

1. Open Whitepaper_*.tex

2. Press F1 to trigger a fast compilation

*NB: this will take a while on the first compilation as some necessary plugins are downloaded on the fly*
