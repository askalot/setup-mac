# Ruby

## Install chruby

```
brew install ruby-install chruby
```

## Install latest version of Ruby

```
ruby-install --latest ruby
```

## Disable gem documents installation

Edit `~/.gemrc` and add:

```
gem: --no-document
```

## Customise IRB

Edit `~/.irbrc` and add:

```
IRB.conf[:PROMPT_MODE] = :SIMPLE
IRB.conf[:AUTO_INDENT_MODE] = false
```

