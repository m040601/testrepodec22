Tue Dec 13 07:24:50 AM WET 2022


```
!gh repo xxx alias in gitconfig
```


```
[alias]
    # Partial migration from hub to gh cli
    # hub works fine but clearly isn't maintained (auth is broken:
    # https://github.com/github/hub/issues/2655)
    cl = !gh repo clone
    browse = !bash -c 'gh pr view --web || gh repo view --web'
    fork = !gh repo fork --remote --remote-name untitaker
    create = !gh repo create --source . --remote origin
```

Tue Dec 13 07:45:54 AM WET 2022
