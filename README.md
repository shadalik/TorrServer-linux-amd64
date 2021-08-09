# TorrServer (by YouROK) Dockerfile

## Usage

```
docker run -d \
	-p 8090:8090 \
	-v torrserver-data:/torrserver \
	--restart always \
	--name torrserver-amd64 \
	shadalik/torrserver-amd64
```

## Parameters

* `-p 8090:8090` - TorrServer port
* `-v torrserver-data:/torrserver` - where TorrServer store config files
* `--name torrserver-amd64` - container name

## Info

* To monitor the logs of container in realtime `docker logs torrserver-amd64`

## Versions
+ **06.08.2020:** TorrServer ver. MatriX.102
+ **06.08.2020:** TorrServer ver. 1.1.77
+ **28.07.2020:** TorrServer ver. 1.1.76_24
+ **04.11.2019:** TorrServer ver. 1.1.76
+ **14.10.2019:** TorrServer ver. 1.1.75
+ **17.07.2019:** TorrServer ver. 1.1.69
