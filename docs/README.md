# `ds`

**Usage**:

```console
$ ds [OPTIONS] COMMAND [ARGS]...
```

**Options**:

* `--install-completion`: Install completion for the current shell.
* `--show-completion`: Show completion for the current shell, to copy it or customize the installation.
* `--help`: Show this message and exit.

**Commands**:

* `get-run`: Get the active run
* `init`: Initialise a datakit run
* `load`: Load data into configuration variable
* `new`: Generate a new datakit and algorithm scaffold
* `reset`: Reset datakit to clean state
* `run`: Execute the active run
* `set`: Set a variable value
* `set-run`: Set the active run
* `show`: Print a variable value
* `view`: Render a view locally

## `ds get-run`

Get the active run

**Usage**:

```console
$ ds get-run [OPTIONS]
```

**Options**:

* `--help`: Show this message and exit.

## `ds init`

Initialise a datakit run

**Usage**:

```console
$ ds init [OPTIONS] [RUN_NAME]
```

**Arguments**:

* `[RUN_NAME]`: Name of the run you want to initialise in the format [algorithm].[run name]

**Options**:

* `--help`: Show this message and exit.

## `ds load`

Load data into configuration variable

**Usage**:

```console
$ ds load [OPTIONS] VARIABLE_NAME PATH
```

**Arguments**:

* `VARIABLE_NAME`: Name of variable to populate  [required]
* `PATH`: Path to data to ingest (xml, csv)  [required]

**Options**:

* `--help`: Show this message and exit.

## `ds new`

Generate a new datakit and algorithm scaffold

**Usage**:

```console
$ ds new [OPTIONS] ALGORITHM_NAME
```

**Arguments**:

* `ALGORITHM_NAME`: Name of the algorithm to generate  [required]

**Options**:

* `--help`: Show this message and exit.

## `ds reset`

Reset datakit to clean state

Removes all run outputs and resets configurations to default

**Usage**:

```console
$ ds reset [OPTIONS]
```

**Options**:

* `--help`: Show this message and exit.

## `ds run`

Execute the active run

**Usage**:

```console
$ ds run [OPTIONS]
```

**Options**:

* `--help`: Show this message and exit.

## `ds set`

Set a variable value

**Usage**:

```console
$ ds set [OPTIONS] VARIABLE_REF VARIABLE_VALUE
```

**Arguments**:

* `VARIABLE_REF`: Either a variable name, or a table reference in the format [resource name].[primary key].[column name]  [required]
* `VARIABLE_VALUE`: Value to set  [required]

**Options**:

* `--help`: Show this message and exit.

## `ds set-run`

Set the active run

**Usage**:

```console
$ ds set-run [OPTIONS] [RUN_NAME]
```

**Arguments**:

* `[RUN_NAME]`: Name of the run you want to enable

**Options**:

* `--help`: Show this message and exit.

## `ds show`

Print a variable value

**Usage**:

```console
$ ds show [OPTIONS] VARIABLE_NAME
```

**Arguments**:

* `VARIABLE_NAME`: Name of variable to print  [required]

**Options**:

* `--help`: Show this message and exit.

## `ds view`

Render a view locally

**Usage**:

```console
$ ds view [OPTIONS] VIEW_NAME
```

**Arguments**:

* `VIEW_NAME`: The name of the view to render  [required]

**Options**:

* `--help`: Show this message and exit.
