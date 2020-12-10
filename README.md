# rundeck
rundeck

## installation
https://docs.rundeck.com/downloads.html

### Debian

```bash
# apt install -y hyperv-daemons vim curl wget mc software-properties-common
```

#### pre-requis
* uuid-runtime
* OpenJDK 8 (Headless)
source : [How to install openjdk-8-jdk on Debian 10 (Buster)?](https://stackoverflow.com/a/61902164/7097233)

```bash
# apt install -y uuid-runtime
# apt-add-repository 'deb http://security.debian.org/debian-security stretch/updates main'
# apt-get update
# apt-get install openjdk-8-jdk-headless
```

