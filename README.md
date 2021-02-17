## Download/Run the Apache Guacamole Script for RHEL 7 and CentOS 7

Download the `guac-install.sh` script from this repo:
```
wget https://raw.githubusercontent.com/LochStudios/guacamole-install-rhel-7/master/guac-install.sh
```
If installing a custom Guacamole extension, download it as well and take note of its file name and path. See [here](https://github.com/Zer0CoolX/guacamole-install-rhel/wiki/Customizing-the-Apache-Guacamole-Login-Screen) for more details

Make the `guac-install.sh` script executable:
```
chmod +x guac-install.sh
```
Run the script as sudo/root:
```
./guac-install.sh
```
