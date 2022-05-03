# AURIN
An easy way to install AUR package with custom Github mirror ability.
> For Chinese users & Other Countries

## Where to install
For Users: `~/.local/bin`. For Root: `/usr/local/bin`

## ArchLinux
Example:
```
aurin https://aur.archlinux.org/xxxxxx.git

# Or Package Name eg. yay
aurin -p yay
```

## Manjaro
```
# The same way
```

### Help
```
aurin [arg]

arg:
    -i | --install    install through buildin mirror
    -m | --mirror     custom aur domain
                            eg.
                            aurin -m githubmirror.xx aur_git_url
                            aurin -m githubmirror.xx raw.xxxxx.xx[optional] aur_git_url
    -d | --default    default github domain
    -p | --package    use simple package name eg. yay
    -b | --bin        copy this file to PATH
                            eg. update:
                            aurin -b u
    -t | --tmp-dir    custom tmp directory [default /tmp]
                            eg.
                            aurin -t ~/.tmp
    -u | --uninstall  uninstall this AUR tool
    -h | --help       show help
```

### Issue
- [x] Free to submit an issue.
