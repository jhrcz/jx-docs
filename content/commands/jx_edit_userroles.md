---
date: 2018-09-12T15:30:22Z
title: "jx edit userroles"
slug: jx_edit_userroles
url: /commands/jx_edit_userroles/
---
## jx edit userroles

Edits the roles associated with a User

### Synopsis

Edits the Roles associated with a User

```
jx edit userroles [flags]
```

### Examples

```
  # Prompt the CLI to pick a User from the list then select which Roles to update for the user
  jx edit userrole
  
  
  # Update a user to a given set of roles
  jx edit userrole --l mylogin -r foo -r bar
  "
```

### Options

```
  -b, --batch-mode                In batch mode the command never prompts for user input
      --headless                  Enable headless operation if using browser automation
  -h, --help                      help for userroles
      --install-dependencies      Should any required dependencies be installed automatically
  -l, --login string              The user login name
      --no-brew                   Disables the use of brew on MacOS to install or upgrade command line dependencies
  -r, --role stringArray          The roles to set on a user
      --skip-auth-secrets-merge   Skips merging a local git auth yaml file with any pipeline secrets that are found
      --verbose                   Enable verbose logging
```

### SEE ALSO

* [jx edit](/commands/jx_edit/)	 - Edit a resource

###### Auto generated by spf13/cobra on 12-Sep-2018