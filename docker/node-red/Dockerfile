FROM nodered/node-red:4.0.9

#
# Add nodes modules for Node-RED
#   https://nodered.org/docs/getting-started/docker
#
COPY package.json .
RUN npm install --unsafe-perm --no-update-notifier --no-fund --only=production
