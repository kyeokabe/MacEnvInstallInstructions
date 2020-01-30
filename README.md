**install brew** (desktopMac, MBP12)

**install python** (desktopMac, MBP12)

**install pip** (desktopMac)

**install pipenv** (desktopMac, MBP12)

```pip3 install pipenv```

**install virtual environment & virtual environment wrapper** (desktopMac ... pipenv better...? -> don't need)

```pip install virtualenv --user```

```pip install virtualenvwrapper --user```

[**install pyenv**](https://opensource.com/article/19/6/virtual-environments-python-macos) (desktopMac)

```brew install pyenv```

[**install zlib and SQLite**](https://opensource.com/article/19/6/virtual-environments-python-macos) (desktopMac)

```brew install zlib sqlite```

```export LDFLAGS="-L/usr/local/opt/zlib/lib -L/usr/local/opt/sqlite/lib"```
```export CPPFLAGS="-I/usr/local/opt/zlib/include -I/usr/local/opt/sqlite/include"```
