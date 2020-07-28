# TorrServer (by YouROK) Dockerfile

## Usage

```
docker run -d \
	-p 8090:8090 \
	-v torrserver-data:/torrserver \
	--restart always \
	--name torrserver-amd64 \
```

## Parameters

* `-p 8090:8090` - TorrServer port
* `-v torrserver-data:/torrserver` - where TorrServer store config files
* `--name torrserver-amd64` - container name

## Info

* To monitor the logs of container in realtime `docker logs torrserver-amd64`

## Version
* TorrServer ver. 1.1.69
