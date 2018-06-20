# splunk

Enterprise:
```console
docker run -d -env SPLUNK_START_ARGS="--accept-license --answer-yes --seed-passwd changeme" -e "SPLUNK_USER=root" -p "8000:8000" ttldtor/splunk:enterprise:latest
```

Universal Forwarder:
```console
docker run -d -env SPLUNK_START_ARGS="--accept-license --answer-yes --seed-passwd changeme" -e "SPLUNK_USER=root" -p "8000:8000" ttldtor/splunk:universalforwarder:latest
```