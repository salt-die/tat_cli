# tat_cli
A command-line tool to colorize terminal output with regex. Supports nested groups and 24-bit colors.

Example usage:

```sh
$ echo "start [121 45567 345] - [454 45563 676] end" | tat "(\[(\d(\d\d)) (\d(\d(\d)\d)\d) ((\d\d)\d)\])"
```

How it looks:

![Preview](https://raw.githubusercontent.com/salt-die/tat_cli/main/preview.png)
