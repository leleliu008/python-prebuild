# python-prebuild
auto build latest python static linking stand alone executable using GitHub Action

## how to use
```
curl -LO https://github.com/leleliu008/python-prebuild/releases/download/3.9.5/python-3.9.5-x86_64-linux-glibc.tar.xz
tar xf python-3.9.5-x86_64-linux-glibc.tar.xz -C /opt
export PATH=/opt/python-3.9.5-x86_64-linux-glibc/bin:$PATH
```

**Note:** installation dir must be `/opt/python-3.9.5-x86_64-linux-glibc`.
