# Microsoft SQL Server BASH Script

Bash script to install Microsoft SQL Server on Linux.

SQL Server 2017 has the following system requirements for Linux:

|   |        |
| ------------- |:--------------|
| Memory        | 3.25 GB |
| File System   | XFS or EXT4 |
| Disk space	      | 6 GB     |
| Processor speed   | 2 GHz      |
| Processor cores   | 2 cores |
| Processor type    | x64-compatible only  |

Usage:

RHEL 7 > 7.5:

```bash
wget https://raw.githubusercontent.com/gzuckerman/mssqlserver-install-script/master/mssqlserver-rhel-75.sh && chmod u+x mssqlserver-rhel.sh && sudo ./mssqlserver-rhel.sh

```
![Command for RHEL 7.5](https://s3-eu-west-1.amazonaws.com/s3.gregoryzuckerman.dev/rhel75-v2.svg)

Fedora 29:

```bash
wget https://raw.githubusercontent.com/gzuckerman/mssqlserver-install-script/master/mssqlserver-fedora-29.sh && chmod u+x mssqlserver-rhel.sh && sudo ./mssqlserver-rhel.sh

```

Ubuntu 16.04:

```bash
wget https://raw.githubusercontent.com/gzuckerman/mssqlserver-install-script/master/mssqlserver-ubuntu-16.04.sh && chmod u+x mssqlserver-ubuntu.sh && sudo ./mssqlserver-ubuntu.sh

```

Ubuntu 18.04:

```bash
wget https://raw.githubusercontent.com/gzuckerman/mssqlserver-install-script/master/mssqlserver-ubuntu-18.04.sh && chmod u+x mssqlserver-ubuntu.sh && sudo ./mssqlserver-ubuntu.sh

```
