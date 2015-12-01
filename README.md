# Nodejs application as service

### Usage

Rename nodejs.conf to <AppName>.conf copy under

```sh
$ /etc/init/<AppName>.conf
```

Rename nodejs.sh to <AppName> copy under

```sh
$ /etc/init.d/<AppName>
```
Change the below variables inside the nodejs.conf and nodejs.sh:

```sh
:service_name=>"<AppName>",
:server_file=>"<your server.js file for node project>",
:app_dir=>"<directory of your project>",
:log_directory=>"<location of the log file to save>"
```
   


