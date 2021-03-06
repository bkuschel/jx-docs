---
date: 2018-10-15T09:26:50Z
title: "jx upgrade ingress"
slug: jx_upgrade_ingress
url: /commands/jx_upgrade_ingress/
---
## jx upgrade ingress

Upgrades Ingress rules

### Synopsis

Upgrades the Jenkins X Ingress rules

```
jx upgrade ingress [flags]
```

### Examples

```
  # Upgrades the Jenkins X Ingress rules
  jx upgrade ingress
```

### Options

```
  -b, --batch-mode                In batch mode the command never prompts for user input
      --cluster                   Enable cluster wide Ingress upgrade
      --headless                  Enable headless operation if using browser automation
  -h, --help                      help for ingress
      --install-dependencies      Should any required dependencies be installed automatically
      --log-level string          Logging level. Possible values - panic, fatal, error, warning, info, debug. (default "info")
      --namespaces stringArray    Namespaces to upgrade
      --no-brew                   Disables the use of brew on MacOS to install or upgrade command line dependencies
      --services stringArray      Services to upgrdde
      --skip-auth-secrets-merge   Skips merging a local git auth yaml file with any pipeline secrets that are found
      --skip-certmanager          Skips certmanager installation
      --verbose                   Enable verbose logging
```

### SEE ALSO

* [jx upgrade](/commands/jx_upgrade/)	 - Upgrades a resource

###### Auto generated by spf13/cobra on 15-Oct-2018
