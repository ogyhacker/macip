# macip
<h1>This tool is only work for the wlan0 interface </h1>
<h3>This will help you to change your macadress and the ip adress of your system .</h3> 
<h3>You can select your custom macadress(extra 5 layers) and ip adress</h3>

## Software Requirements:
The following OSs are officially supported:

- Debian 8+
- Kali Linux Rolling 2018.1+

The following OSs are likely able to run macip:

- Arch Linux
- Manjaro Linux
- BlackArch Linux
- Deepin 15+
- Elementary
- Fedora 22+
- Linux Mint
- Parrot Security
- Ubuntu 15.10+
- Void Linux

## Setup

### update your system

```bash
apt update
```

### upgrade your system

```bash
apt upgrade -y
```

### Git's Quick Install

**NOTE**:
- Installation must be done with superuser privileges. If you are not using the root account (as default with Kali Linux), prepend commands with `sudo` or change to the root user before beginning.
- Your package manager may be different to `apt`. You will also need an X server running, either on the system itself, or on your local system.

```bash
sudo apt-get -y install git
git clone https://github.com/ogyhacker/macip.git
```
### File permission
This will generate the output file for `macip.sh`.
To make that file executable .

```bash
chmod +x macip.sh
```
### launch the tool
You can launch the tool by using the file.

```bash
./macip.sh
```
## Example Usage

macip's Main Menu:
