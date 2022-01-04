## What are in the PureConnect ICWS Postman Collection v2.1.0? 
***How to:***
- ```POST``` connect to PureConnect Cloud and Permise enviroment
-  ```GET``` retrive IC user status
-  ```PUT``` create subscription to handler-sent notifications
- ```POST``` send request to a custom handler
-  ```GET``` retrieves any queued notifications

## Prerequisites
- ICWS SDK license ([I3_FEATURE_ICWS_SDK](https://help.genesys.com/pureconnect/mergedProjects/wh_tr/mergedProjects/wh_tr_icws_sdk_icg/desktop/what_is_the_icws_sdk.htm)) for your PureConnect environment
- Install [Postman](https://www.postman.com/downloads/)

## How to setup your environment
- Download & install [Postman](https://www.postman.com/downloads/)
- Import [Postman Environment](pureconnect-icws.postman_environment.json) ([how to import Postamn environment](https://www.youtube.com/watch?v=bzquMXmCLUQ))
- In the imported Postman Environment modify ```server```, ```user```, ```password``` variables
- Import [Postman Collection](pureconnect-icws.postman_collection.json) ([how to import Postamn collection](https://learning.postman.com/docs/getting-started/importing-and-exporting-data/#importing-postman-data))
- Select an active environment ([how to select environment](https://learning.postman.com/docs/sending-requests/managing-environments/#selecting-an-active-environment))


> **This project/work is my own and is in no way associated/attributed to any current or former employer. See [license file](LICENSE) regarding permissions, limitations, and  conditions. I do advise testing any of the provided scripts in a DEV or non-PROD environment first before running it in a PROD environment. For some large output-file base scripts it is better to run them outside of the peak hours.**
