# Pod
Polls data from serial and sends telemetry/receives commands over MQTT

## Requirements
* Python 3.6

## Install
```bash
git clone git@github.com:NYU-Hyperloop/Pod.git
cd Pod
virtualenv venv
source venv/bin/activate # Windows: source venv/Scripts/activate
pip install -r requirements
```

## Run
There is a sample config along with a CA cert and client cert/key pair in the `test/` directory. **DO NOT** use these in production.

```bash
python pod.py -c test/pod.cfg
```
