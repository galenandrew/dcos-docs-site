---
layout: layout.pug
navigationTitle:  dcos task log
title: dcos task log
menuWeight: 1
excerpt: Displaying the task log

enterprise: false
---


# Description
Print the task log.

# Usage

```bash
dcos task log <task> <file> [OPTION]
```

# Options

| Name, shorthand | Default | Description |
|---------|-------------|-------------|
| `--completed`   |             | Print completed and in-progress tasks. |
| `--follow`   |             |  Dynamically update the log. |
| `--lines=N`   |     10      |  Print the last N lines. |

# Positional arguments

| Name, shorthand | Default | Description |
|---------|-------------|-------------|
| `<task>`   |             |  A full task ID, a partial task ID, or a regular expression. |
| `<file>`   |  stdout  |  Specify the sandbox file to print. |

# Parent command

| Command | Description |
|---------|-------------|
| [dcos task](/1.11/cli/command-reference/dcos-task/)   | Manage DC/OS tasks. |

# Examples

For an example, see the [documentation](/1.11/monitoring/logging/).
