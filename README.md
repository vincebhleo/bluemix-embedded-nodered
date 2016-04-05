# bluemix-embedded-nodered
Run Node-RED from within an Express Server

Check out the original boilerplate code https://github.com/watson-developer-cloud/node-red-bluemix-starter.

This repo is an example of running Node-RED in embedded mode within Express for using OAuth and other packages that may not run in a vanilla Node-RED.  

The following features are not supported in embedded and should be configured within Express: uiHost, uiPort, httpAdminAuth, httpNodeAuth, httpStatic, httpStaticAuth, https. The updated adminAuth password protection function works in embedded mode, replacing httpAdminAuth. 

[![Deploy to Bluemix](https://bluemix.net/deploy/button.png)](https://bluemix.net/deploy?repository=https://github.com/slkaczma/bluemix-embedded-nodered)
