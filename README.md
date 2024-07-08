This is a minimal Visual Builder demo site

## Getting Started

Configure your local env by adding .env.local file in the root folder
Make sure to add the following values:

```bash
# Optimizely Global
OPTIMIZELY_DEBUG=0

# Optimizely Graph
OPTIMIZELY_GRAPH_GATEWAY=https://beta.cg.optimizely.com/
OPTIMIZELY_GRAPH_APP_KEY=YOUR_KEY_HERE
OPTIMIZELY_GRAPH_SECRET=YOUR_SECRET_HERE
OPTIMIZELY_GRAPH_SINGLE_KEY=YOUR_SINGLE_KEY_HERE
OPTIMIZELY_GRAPH_UPDATE_DELAY=2000
OPTIMIZELY_GRAPH_QUERY_LOG=0

# Optimizely CMS
OPTIMIZELY_CMS_URL=YOUR_INSTANCE_URL_HERE
OPTIMIZELY_CMS_CLIENT_ID=YOUR_CLIENT_HERE
OPTIMIZELY_CMS_CLIENT_SECRET=YOUR_CLIENT_SECRET_HERE
OPTIMIZELY_CMS_USER_ID=YOUR_USER_ID_HERE

NODE_TLS_REJECT_UNAUTHORIZED=0
```

Then make sure you've got your local environment (Make sure use latest stable node, e.g. 18.17.0):
```bash
yarn install
```

Finally, start the local development server
```bash
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
