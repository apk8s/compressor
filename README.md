# Compressor

Object processing demo. Minio object compressor (gzipper).

This Go application and container is for demonstrating object processing applications for apk8s.

```shell script
docker build -t apk8s/compressor .

docker run -e ENDPOINT=$ENDPOINT -e ACCESS_KEY_ID=$ACCESS_KEY_ID -e ACCESS_KEY_SECRET=$ACCESS_KEY_SECRET apk8s/compressor -f=upload -k=customers.csv -t=processed
```
