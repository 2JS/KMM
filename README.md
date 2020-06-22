# KMM

**Kerbal Space Program Mod Manager**, or **KMM** aimed at easiness and simplicity. Simple CLI, user friendly GUI application, concurrent installation, dependency handling, multi-version handling.

## Suggested functions

### Simple

```bash
$ kmm add mechjeb # detects host's KSP version and install mechjeb
$ kmm add mechjeb rss # install mechjeb, rss, and their dependencies
```

### More Power

Other commands with several options.

```bash
$ kmm add rss --ksp-version 1.7.3 # install latest compatible version of rss
$ kmm add rss:v16.4 --no-dependency # install specific version without installing dependencies
$ kmm add https://github.com/KSP-RO/.../RealSolarSystem_v16.4.zip # install from given URL. Archive, Git
$ kmm del rss # delete rss and its dependencies. We need thoughtful consideration when deleting dependencies.
$ kmm switch 1.8.1 # change mod versions compatible to KSP 1.8.1
```

