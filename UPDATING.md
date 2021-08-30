# How to re-build or update the image

Find up-to-date IB Gateway and IBController binaries.
Pass these into docker build:

`docker build --build-arg  IBGATEWAY_URL=https://download2.interactivebrokers.com/installers/ibgateway/stable-standalone/ibgateway-stable-standalone-linux-x64.sh --build-arg  IBCONTROLLER_URL=https://github.com/ib-controller/ib-controller/releases/download/3.4.0/IBController-3.4.0.zip .`