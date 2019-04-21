# trackpoint
Simple script to enable/disable trackpoint on Thinkpad laptops.

If you are user of the i3wm you can  bind a ThinkVantage blue button to toggle this script.
Add to your `~/.config/i3/config` file (or wherever you store it):
```
bindcode 156 exec --no-startup-id ~/trackpoint
```

## Tested on ##
OS: Fedora, Ubuntu

DEVICE: X220, X230, X1 Carbon, T440
