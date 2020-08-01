# SSH

## Switch to config directory

```
mkdir ~/.ssh && cd ~/.ssh
```

## Generate new SSH key

```
ssh-keygen -t rsa -b 4096 -C "username@domain.tld" -f id_rsa
```

Save to password manager:
* SSH password
* Key fingerprint
* Randomart image

## Start ssh-agent in background

```
eval "$(ssh-agent -s)"
```

## Add config

```
touch ~/.ssh/config
```

Copy `https://raw.githubusercontent.com/askalot/dotfiles/master/sshconfig` to `~/.ssh/config`.

## Add SSH private key to ssh-agent

```
ssh-add -K ~/.ssh/id_rsa
```

