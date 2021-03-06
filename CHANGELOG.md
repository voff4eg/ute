### 0.1.0-pre
* Re-stack to Hapi, Cluster2, NConf.

### 0.0.6
* Add request body parsing for POST data
* Add handlers module for convenient error response handling
* Add isoToLocale util function
* Expose all static resources instead of individual images, scripts, and styles

### 0.0.5
* Upgrade connect-assetmanager to v0.0.27 to serve 304s on unmodified static resources (JavaScript, CSS, images)
 
### 0.0.4
* Upgrade all deps to latest, Express to v2.5.9
* Bump min node engine requirement to v0.6

### 0.0.3 
* Handle process uncaught exception, log error instead of exit
* Static asset only includes resources with file.ext format

### 0.0.2
* Add custom express app config / set up hook
* Pass error to error page templates
* Pass process.env and run ID to all page templates

### 0.0.1
* Initial version
