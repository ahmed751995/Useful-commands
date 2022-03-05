# Useful linux commands 

these are a list of useful linux commands  for me

### turn Arc-them font color to black

```bash
  sudo find /usr/share/themes/Arc -name "*" -type f -exec sed -i 's/'5C616C'/'000000'/gI' {}  \;
```

### Add Power Line to terminal

```bash
    if [ -f `which powerline-daemon` ]; then
      powerline-daemon -q
      POWERLINE_BASH_CONTINUATION=1
      POWERLINE_BASH_SELECT=1
      . /usr/share/powerline/bindings/bash/powerline.sh
    fi
```


