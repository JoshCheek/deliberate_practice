Deliberate Practice
===================

Readline keybindings
--------------------

`C-a`, `C-e`, `M-b`, `M-f`, `C-b`, `C-f`, `C-u`, `C-k`, `C-y`, `M-delete`, `M-d`, `C-d`, `C-n`, `C-p`

Integer literals
----------------

```sh
ruby -e 'p 10, 0b10, 010, 0x10'
```


Exit statuses
-------------

```sh
$ fish
$ true
$ echo $status  # or in bash: `echo $?`
$ false
$ echo $status
$ ruby -e 'exit 0'
$ echo $status
$ ruby -e 'exit 1'
$ echo $status
$ ruby -e 'exit 255'
$ echo $status
$ ruby -e 'exit 256'
$ echo $status
```

Possibilities
=============

* recreate unix programs (cat, grep, cp, mv, ls, env, ...)
* shell piping and redirection (`|`, `>`, `2>`, `2>&1`, `>>`, `<`)
* HTTP (nc / webserver / etc)
* shell quoting / splitting / glob patterns
