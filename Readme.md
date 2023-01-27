# fc in Fish

Simulate `fc` command in fish

## Installation
Install with [Fisher](https://github.com/jorgebucaran/fisher "fish plugin manager"):
```console
fisher install lengyijun/fc-fish
```

## Support

```
# edit the last command
fc
fc -1

# edit the second last command
fc -2
```

```
# view last 16 command
fc -l 

# view last 16 command in reverse order
fc -l -r
```

```
# edit last 3 command
fc -3 -1
```

## Not support
```
# fish doesn't have (positive) key for history
fc 15 22 
```

```
# -s not supported
fc -s "foo"
```

```
# zsh specific parameter
fc -fl
fc -ld
```

## Note

In fish, we can use `upparrow alt+e` or `upparrow alt+v` to edit previous command

## Similar plugin
- [fishbang](https://github.com/BrewingWeasel/fishbang) - Bash bang command for fish

## Reference
1. `man fc`
2. https://github.com/fish-shell/fish-shell/issues/5030
3. https://github.com/fish-shell/fish-shell/pull/7121

