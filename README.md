# .gitconfig

My `.gitconfig` settings

## Instructions (macOS)

1) `brew install git-delta`
1) `gh repo clone AshwinSundar/git-config` 
2) `ln -s /path/to/git-config/.gitconfig ~/.gitconfig` - symlink `.gitconfig` to your home directory

Expected Results:

```bash
  $ ls -la ~/ | grep ".gitconfig"
    lrwxr-xr-x@   1 <user>  staff     42 Nov  8 20:00 .gitconfig -> /Users/<user>/.config/git/.gitconfig
```

Try running `git diff` to see the new delta pager
