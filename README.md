# splunk

Version: 6.3.3

Build: f44afce176d0

Enterprise:
```console
docker run -d --env SPLUNK_START_ARGS="--accept-license --answer-yes --seed-passwd changeme" -e "SPLUNK_USER=root" -p "8000:8000" ttldtor/splunk:enterprise-latest
```

Universal Forwarder:
```console
docker run -d --env SPLUNK_START_ARGS="--accept-license --answer-yes --seed-passwd changeme" -e "SPLUNK_USER=root" -p "8000:8000" ttldtor/splunk:universalforwarder-latest
```

Enterprise (jdbc):
```console
docker run -d --env SPLUNK_START_ARGS="--accept-license --answer-yes --seed-passwd changeme" -e "SPLUNK_USER=root" -p "8000:8000" ttldtor/splunk:enterprise-jdbc-latest
```

Universal Forwarder (jdbc):
```console
docker run -d --env SPLUNK_START_ARGS="--accept-license --answer-yes --seed-passwd changeme" -e "SPLUNK_USER=root" -p "8000:8000" ttldtor/splunk:universalforwarder-jdbc-latest
```