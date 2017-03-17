# Tool to migrate short nix-{env,shell,build,instantiate,...} options to long ones

Main use case is making documention, blog posts or example code
more accessible. Will change e.g.

`nix-env -e vim` to `nix-env --uninstall vim`

Usage:

```
./nix-short-to-long PATH_IN_GIT_REPO
```
