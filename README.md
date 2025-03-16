**Patches**
- autostart scripts
- bar padding
- stacker
- tag preview
- xresources
- hide vacant tags
- fullgaps

**Setup**
`git clone git@github.com:StackGrandiose/sgdwm.git`
- Create `autostart.sh` and `autostart_blocking.sh` in ~/.local/share/dwm/` 
    - dwm doesn't start unless `autostart_blocking.sh` has stopped, so do not start any X programs or programs that are meant to run in the background in this file.
- `sudo make clean install`

**Source**
[dwm - dynamic window manager | suckless.org software that sucks less](https://dwm.suckless.org/)
