# trackpoint
Simple script to enable/disable trackpoint on Thinkpad laptops.
Works for all laptops **BEFORE** x240/T440/T540/xn40 and higher.
If you are user of the i3wm you can  bind a . ThinkVantage blue button to toggle this script.
Add to your `~/.config/i3/config` file (or wherever you store it):
```
bindcode 156 exec --no-startup-id ~/trackpoint
```

# TODO
- Make it work on xn40 and higher;
- Make a script to bind this one to the ThinkVantage button.
