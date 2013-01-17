# runloop

start a program, restart if it crashes, and cleanup any child processes

== usage
```
runloop start COMMAND  # start COMMAND
runloop stop           # stop COMMAND (run in this dir)
runloop restart        # stop, then start again
```

`runloop` with save two files in the local dir,
`.runloop-pid` the pid of the current job,
and `.runloop-command` the command run.

## License

MIT
