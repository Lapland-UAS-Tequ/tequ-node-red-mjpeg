tequ-node-red-mjpeg
=====================

Provides MJPEG data stream to [AI] Detect subflows.

## Install

Run the following command in your Node-RED user directory - typically `~/.node-red`

        npm install tequ-node-red-mjpeg

## Information

Node to connect MJPEG data sources
- Connects to MJPEG data stream
- Outputs JPEG image buffers
- Outputs limited stream and original stream
- ID parameter is set into topic
- Automatically reconnects every ~30 seconds if connection is lost

Dependencies:
- https://flows.nodered.org/node/node-red-contrib-multipart-stream-decoder
- https://flows.nodered.org/node/node-red-contrib-msg-speed
