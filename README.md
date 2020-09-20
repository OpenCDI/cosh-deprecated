COntainer SHell native toolkit for /bin/sh

# ABOUT

Container-oriented shell toolkit for pod operation and GUI sandboxing.

# USAGE
```
cosh-0.0.9  container shell toolkit for /bin/sh
usage:
  cosh [-cuo] <command>
  cosh [list|images|help]
options:
  -c container		specify target container
  -u username		specify target user
  -o|--onetime		make temporary container to execute commands
subcommands:
  list 			list container
  images 		list container images
  help [--all] 		show this help
```

# REQUIREMENT

shelib (@core) >=0.5.0

# INSTALL 

```
shef install https://github.com/okadash/cosh
```
