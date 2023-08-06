# server-scanner
***Server Scanner detect rootkit and backdoor***

## Setup
**Setup ✅**

```bash
$ curl -sL https://deb.nodesource.com/setup_12.x | sudo bash -
$ sudo apt-get -y install nodejs
$ git clone https://github.com/amirexsploit/serverscanner
$ cd serverscanner
$ configure your path first on line 4 in index.js
$ npm install
$ node index.js
```
Setup Your path

```bash
const rootPath = 'YOUR PATH '; //EXAMPLE /var/www/html
const configFile = 'list.json';
```


## Supported features

| Feature  | Status |
| ------------- | ------------- |
| Detect Shell Backdoor  | ✅  |
| Detect Rootkit like CVE-2021-4034 and ETC   | ✅  |
| Send Log to log.txt  | ✅  |
| No auto delete,at least you can check the file first | ✅  |


## Screenshots
![Screenshots 1](https://github.com/amirexsploit/serverscanner/blob/main/scrinshoot/scrennshots-1.jpg)
