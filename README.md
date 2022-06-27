# chromium-sdk
Chromium A C

## Why?
NWJS Is a CEF Build of Chromium + a Chromium/Google App (It keeps the google apps api's alive) but exposes not the whole tab functionality. 
It also ships with a nodejs build as shared lib that you can disable optional to get only the CEF Build + App 

It comes in handy to use it exclusive so no additional nodejs install for the system should be needed. 

## How?

Download NWJS copy over bin and lib from npm 
```
NPM_CONFIG_PREFIX=$PWD npm install -g npm
ln -s ../nw bin/
ln -s ../nw bin/node
```
