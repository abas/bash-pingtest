# Pingtest 
> ### How to Basic

```bash
  # clone this repo
  $ git clone repo_url ~/bash-pingtest
  $ cd ~/bash-pingtest
  $ chmod +x pingtest

  # basic usage
  $ /path/to/pingtest [prefix_ip] [start_point] [end_point]
  # example
  $ /path/to/pingtest 192.168.0 1 128
  # you also can make start_point bigger than from end_point
  $ /path/to/pingtest 192.168.0 128 1
```

> ### Issue

```bash
[ ] some function may not work correctly on some os
```

<kankuu> dont be hesitate to make `Issue` and `Pull Request` :>