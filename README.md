# Elementum's 3rd Factor Authentication

## Summary
This repo contains the nessessary install scripts and drivers to support Elementum's 3rd Factor Auth solution.

## Principles
- **Commitment to code quality:** As Elementums, we are committed to delivering disruptive tools for supply chain management, starting with high quality and lucent code.
- **Enhance the Flywheel:**Any breakage to the build, delays shipping product, and take people and teams away from critical company efforts.
- **Life @Elementum: Work Hard, Play Hard :** We want everyone to have fun at Elementum, but we want everyone to do this in a safe way for our co-workers and our product.

## What's in this Repo
###install.sh### - Script to download the drivers and install.

Use the following command line to install the breathalizer drivers:
```
curl https://raw.githubusercontent.com/eltchung/3FA/master/install.sh | /bin/bash
```

**Note:** Yes, I know that piping into bash is very insecure, but hey, your trusty security guy wrote this.  So, it's ok.

###usb_breathalizer.drv### - usb profile and driver for OSX

