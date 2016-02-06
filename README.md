# Tiny Time tracker

[![Dependency Status](https://david-dm.org/danibram/time-tracker-cli.svg)](https://david-dm.org/danibram/time-tracker-cli)

## Usage

[![asciicast](https://asciinema.org/a/35678.png)](https://asciinema.org/a/35678)

```
±❩❩❩ ./bin/timer --help

  Usage: timer [options]

  Tiny time tracker for projects

  Options:

    -h, --help                       output usage information
    -V, --version                    output the version number
    -s, --start <task>               Start the timer task.
    -f, --finish <task>              Stops the timer task.
    -d, --description <description>  Adds a descrpition for the task only in start/stop methods.
    -l, --log <task>                 Logs the timer task.
    -r, --report <task>              Report time of the tasks, searched by kay, you can report all using all as key.
    -e, --export                     Prints the json of all tasks.
```

- To start a task run:
```
$ timer -s <key of the task> -d  <description>
```
- To finish a task run:
```
$ timer -s <key of the task> -d  <description>
```
- You can add a description adding:
```
$ timer -s <key of the task> -d  <description>
$ timer -h <key of the task> -d  <description>
```
- You can also see the timer running:
```
$ timer -l <key of the task>
```

## Development

Run ```npm install;npm run dev``` to watch the proyect, and compile the code automatically.
Run ```npm build``` to build the module.