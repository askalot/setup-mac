# SSH

## Switch to config directory

```
mkdir ~/.ssh && cd ~/.ssh
```

## Generate new SSH key

```
ssh-keygen -t ed25519 -C "username@domain.tld" -f id_ed25519
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
ssh-add -K ~/.ssh/id_ed25519
```

## Copy public key

```
pbcopy < ~/.ssh/id_ed25519
```

Add the public key to the relevant remote machines.
