# python-prebuild
auto build latest python static linking stand alone executable using GitHub Action

## how to use
```
curl -LO https://github.com/leleliu008/git-prebuild/releases/download/2.30.2/git-2.30.2-x86_64-linux-glibc.tar.xz
tar xf git-2.30.2-x86_64-linux-glibc.tar.xz -C /opt
ln -sf /opt/git-2.30.2-x86_64-linux-glibc/bin/git /usr/bin/git
```

**Note:** installation dir must be `/opt/git-2.30.2-x86_64-linux-glibc`.
