---
date: 2020-01-07T19:41:02Z
title: "jx step restore from-backup"
slug: jx_step_restore_from-backup
url: /commands/jx_step_restore_from-backup/
---
## jx step restore from-backup

This step attempts a velero restore from a selected velero backup

### Synopsis

Restores the cluster custom data from the a backup.

```
jx step restore from-backup [flags]
```

### Examples

```
  # executes the step which restores data from a backup
  jx step restore from-backup
```

### Options

```
  -h, --help               help for from-backup
      --latest             This indicates whether to use the latest velero backup as the restore point
      --namespace string   The namespace where velero has been installed (default "velero")
```

### Options inherited from parent commands

```
  -b, --batch-mode   Runs in batch mode without prompting for user input (default true)
      --verbose      Enables verbose output
```

### SEE ALSO

* [jx step restore](/commands/jx_step_restore/)	 - restore [command]

###### Auto generated by spf13/cobra on 7-Jan-2020