# SITL RTSP Proxy

## Prerequisites

### Debian/Ubuntu

```
sudo apt install build-essential cmake
sudo apt install build libgstreamer1.0-dev libgstrtspserver-1.0-dev
```

## Build

```
cd sitl_rtsp_proxy
cmake -Bbuild -H.
cmake --build build
```

## Run

```
build/sitl_rtsp_proxy
```
