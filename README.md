## What are in the PureConnect ICWS Postman Collection? 
***How to:***
- connect to PureConnect Cloud and Permise enviroment
- connect to PureConnect Cloud and Permise enviroment

## Prerequisites
- ICWS SDK license ([I3_FEATURE_ICWS_SDK](https://help.genesys.com/pureconnect/mergedProjects/wh_tr/mergedProjects/wh_tr_icws_sdk_icg/desktop/what_is_the_icws_sdk.htm)) for your PureConnect environment
- Install [Postman](https://www.postman.com/downloads/)
- Based on your PureConnect environment, you will need to add ```ic_server```, ```ic_username```, ```ic_password```, ```friendlyname``` (for Cloud), ```ic_application_name``` parameters to [icws_cloud_authentication.py](scripts/icws_cloud_authentication.py) or [icws_premise_authentication.py](scripts/icws_premise_authentication.py) file

## How to setup your environment
- Download & install [Postman](https://www.postman.com/downloads/)
- Use one of the following ICWS connection methods based on your PureConnect enviromnet:
  - for [PureConnect On-Premise](scripts/icws_premise_authentication.py)
  - for [PureConnect Cloud via Internet](scripts/icws_cloud_authentication.py) 

> **This project/work is my own and is in no way associated/attributed to any current or former employer. See [license file](LICENSE) regarding permissions, limitations, and  conditions. I do advise testing any of the provided scripts in a DEV or non-PROD environment first before running it in a PROD environment. For some large output-file base scripts it is better to run them outside of the peak hours.**
