# Learning Redis


## Installing Redis on MacOS

```
brew install redis
```

## Running Redis Server

```
[Captains-Bay]🚩 >  redis-server
23888:C 06 Apr 2020 18:29:27.385 # oO0OoO0OoO0Oo Redis is starting oO0OoO0OoO0Oo
23888:C 06 Apr 2020 18:29:27.386 # Redis version=5.0.7, bits=64, commit=00000000, modified=0, pid=23888, just started
23888:C 06 Apr 2020 18:29:27.386 # Warning: no config file specified, using the default config. In order to specify a config file use redis-server /path/to/redis.conf
23888:M 06 Apr 2020 18:29:27.387 * Increased maximum number of open files to 10032 (it was originally set to 4864).
                _._
           _.-``__ ''-._
      _.-``    `.  `_.  ''-._           Redis 5.0.7 (00000000/0) 64 bit
  .-`` .-```.  ```\/    _.,_ ''-._
 (    '      ,       .-`  | `,    )     Running in standalone mode
 |`-._`-...-` __...-.``-._|'` _.-'|     Port: 6379
 |    `-._   `._    /     _.-'    |     PID: 23888
  `-._    `-._  `-./  _.-'    _.-'
 |`-._`-._    `-.__.-'    _.-'_.-'|
 |    `-._`-._        _.-'_.-'    |           http://redis.io
  `-._    `-._`-.__.-'_.-'    _.-'
 |`-._`-._    `-.__.-'    _.-'_.-'|
 |    `-._`-._        _.-'_.-'    |
  `-._    `-._`-.__.-'_.-'    _.-'
      `-._    `-.__.-'    _.-'
          `-._        _.-'
              `-.__.-'

23888:M 06 Apr 2020 18:29:27.392 # Server initialized
23888:M 06 Apr 2020 18:29:27.394 * DB loaded from disk: 0.001 seconds
23888:M 06 Apr 2020 18:29:27.394 * Ready to accept connections
^C23888:signal-handler (1586177983) Received SIGINT scheduling shutdown...
23888:M 06 Apr 2020 18:29:43.699 # User requested shutdown...
23888:M 06 Apr 2020 18:29:43.699 * Saving the final RDB snapshot before exiting.
23888:M 06 Apr 2020 18:29:43.703 * DB saved on disk
23888:M 06 Apr 2020 18:29:43.703 # Redis is now ready to exit, bye bye...
[Captains-Bay]🚩 >  redis-server
23893:C 06 Apr 2020 18:29:54.324 # oO0OoO0OoO0Oo Redis is starting oO0OoO0OoO0Oo
23893:C 06 Apr 2020 18:29:54.324 # Redis version=5.0.7, bits=64, commit=00000000, modified=0, pid=23893, just started
23893:C 06 Apr 2020 18:29:54.324 # Warning: no config file specified, using the default config. In order to specify a config file use redis-server /path/to/redis.conf
23893:M 06 Apr 2020 18:29:54.325 * Increased maximum number of open files to 10032 (it was originally set to 4864).
                _._
           _.-``__ ''-._
      _.-``    `.  `_.  ''-._           Redis 5.0.7 (00000000/0) 64 bit
  .-`` .-```.  ```\/    _.,_ ''-._
 (    '      ,       .-`  | `,    )     Running in standalone mode
 |`-._`-...-` __...-.``-._|'` _.-'|     Port: 6379
 |    `-._   `._    /     _.-'    |     PID: 23893
  `-._    `-._  `-./  _.-'    _.-'
 |`-._`-._    `-.__.-'    _.-'_.-'|
 |    `-._`-._        _.-'_.-'    |           http://redis.io
  `-._    `-._`-.__.-'_.-'    _.-'
 |`-._`-._    `-.__.-'    _.-'_.-'|
 |    `-._`-._        _.-'_.-'    |
  `-._    `-._`-.__.-'_.-'    _.-'
      `-._    `-.__.-'    _.-'
          `-._        _.-'
              `-.__.-'

23893:M 06 Apr 2020 18:29:54.327 # Server initialized
23893:M 06 Apr 2020 18:29:54.327 * DB loaded from disk: 0.000 seconds
23893:M 06 Apr 2020 18:29:54.327 * Ready to accept connections


```
