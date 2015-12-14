# Install 
```
cd ~/.config
git clone https://github.com/dhensen/awesome-wm-config awesome
cd awesome
cp config.lua.dist config.lua
```

##### Notice
If the path ~/.config/awesome already exists, just change it in the git clone line 
to something else. Then point awesome to that rc.lua location like this:
```awesome -c ~/.config/awesome-renamed-or-something/rc.lua```
