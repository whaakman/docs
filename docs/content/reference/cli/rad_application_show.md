---
type: docs
title: "rad application show CLI reference"
linkTitle: "rad application show"
slug: rad_application_show
url: /reference/cli/rad_application_show/
description: "Details on the rad application show Radius CLI command"
---
## rad application show

Show Radius Application details

### Synopsis

Show Radius Application details. Shows the user's default application (if configured) by default.

```
rad application show [flags]
```

### Examples

```

# Show current application
rad app show

# Show specified application
rad app show my-app

# Show specified application in a specified resource group
rad app show my-app --group my-group

```

### Options

```
  -a, --application string   The application name
  -g, --group string         The resource group name
  -h, --help                 help for show
  -o, --output string        output format (supported formats are json, table) (default "table")
  -w, --workspace string     The workspace name
```

### Options inherited from parent commands

```
      --config string   config file (default "$HOME/.rad/config.yaml")
```

### SEE ALSO

* [rad application]({{< ref rad_application.md >}})	 - Manage Radius Applications

