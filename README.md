# PCF Default 503

This repository contains an application that always returns an HTTP 503 status code.

To deploy to PCF:

```
cf push
```

It leverages the [staticfile buildpack](https://docs.cloudfoundry.org/buildpacks/staticfile/index.html), which serves all 
requests via Nginx.
