# Bitfana

Please run:
```
docker run -p 8086:8086 -v $PWD:/var/lib/influxdb influxdb
docker run --name=grafana -p 3000:3000 grafana/grafana
virtualenv .venv
source .venv/bin/activate
pip install -r requirements.txt
python run.py
```
