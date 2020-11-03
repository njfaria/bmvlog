# bmvlog
[<img alt="GitHub release (latest by date)" src="https://img.shields.io/github/v/release/njfaria/bmvlog">](https://github.com/njfaria/bmvlog/releases)
[<img alt="GitHub All Releases" src="https://img.shields.io/github/downloads/njfaria/bmvlog/total">](https://github.com/njfaria/bmvlog/releases/latest)
[<img alt="donate" src="https://img.shields.io/badge/donate-Paypal-green">](https://www.paypal.com/donate?hosted_button_id=ZDTGKU48JP678&source=url)
[<img alt="Suporter Names" src="https://img.shields.io/badge/suporter-names-orange">](/docs/suporternames.md)

logger for Victrons BMV Battery Monitors on Raspberry

Sends data per MQTT to your local broker ( for Home Automation for example ) and to your local Emoncms account.
Interfaces with solpiplog to change the inverter to switch to grid or solar, based on predifined SOC values.
## Instalation
download [<img alt="GitHub release (latest by date)" src="https://img.shields.io/github/v/release/njfaria/bmvlog">](https://github.com/njfaria/bmvlog/releases)
create a folder on your raspberry with explorer or per commandline ''' mkdir bmv '''
copy downloaded zip to bmv folder
unzip the file
execute ''' setup.sh '''

## [Values sent over MQTT](/docs/mqttvalues.md)
## Appearance
![bmvlog](bmvmain.png)
![bmvlog](bmvconfig.jpg)
