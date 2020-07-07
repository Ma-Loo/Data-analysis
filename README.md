# Network Data Analisys (network connection possibility)
xls(x) to json converter, algorithm for data analisys. 
Script will: 
- make decision about probability of network connection between two networks;
- compare the special networking data (VRF's number and region) from json file (generated from JS portal). If there is no json file it will convert it from xls(x) to json;

# OpenVPN automation
The script get number of the persons, their city and names as input. Then automaticly creates the keys and certificates, password and login. The script should be issued in easy-rsa directory like that: "source ./vars && pyhton3.6 script.py"
