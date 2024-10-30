# donor_service_Care2Share

## Overview
Donor service for Care2Share Application (atomic service).
Running on Port 8001.

### Running and Testing on VM
```
source venv/bin/activate
python3 main.py
^Z
bg %1
curl localhost:8001
fg %1
^C
```
On browser, access http://localhost:8001/


### Set up + Running Application Locally
```
sudo apt update

sudo apt install python3 python3-pip -y

git clone https://github.com/cpreston123/donor_service_Care2Share.git

sudo apt install python3.12-venv

sudo python3 -m venv ./venv

source venv/bin/activate

pip install requirements.txt

python main.py

```
See above "Running and Testing on VM" to test application
