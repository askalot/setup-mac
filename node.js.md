# Node.js

## Install n

```
brew install n
```

## Configure permissions

### Create cache folder and take ownership

```
sudo mkdir -p /usr/local/n
sudo chown -R $(whoami) /usr/local/n
```

### Take ownership of node install destinations

```
sudo chown -R $(whoami) /usr/local/bin /usr/local/lib /usr/local/include /usr/local/share
```

## Install latest version of Node.js

```
n latest
```

