# ShopFS Node-Red Service

A node-red based monitoring service that listens to events on the ethereum blockchain

## Pre-requisites (30 mins)

Make sure you are running a [supported version](https://nodered.org/docs/faq/node-versions) of node.js.

## Step 1: Download & Install Node-Red

[For Linux/Mac](https://nodered.org/docs/getting-started/local):
  ```
  sudo npm install -g --unsafe-perm node-red
  ```
  
[For Windows](https://nodered.org/docs/getting-started/windows):
  ```
  npm install -g --unsafe-perm node-red
  ```

## Step 2: Download or Clone repo (2 mins)
```
git clone https://github.com/shopfs/service.git

cd <cloned repo root folder path>

npm install
```

Start node red using command below
```
node-red  --userDir <cloned repo root folder path>
```

Once running, go to: http://localhost:1880
