COntainer SHell toolkit for /bin/sh

# ABOUT

COntainer SHell toolkit for pod operation and GUI sandboxing.

# USAGE
```
cosh-0.1.0  container shell toolkit for /bin/sh
usage:
  cosh [-cufnDo] <command>
  cosh [list|images|copy|help] 
options:
  -c container		specify target container
  -u username		specify target user
  -f file		specify cosh script for the execution
  -n|--network id	specify network bridge
  -D|--data volume	specify docker volume to mount
  -o|--oneshot [cmd]	make temporary container to execute commands
subcommands:
  list [-l|-a]		list container
  images [-f]		list container images
  copy [pod:]<path>	copy a file from/to container
  help [--all]		show this help

```

# REQUIREMENT

shelib (@core) >=0.5.0

# INSTALL 

```
shef install https://github.com/okadash/cosh
```
