# splunk

Version: 7.1.1

Build: 8f0ead9ec3db

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