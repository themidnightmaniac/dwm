My personal build of dwm, which include the following patches:
urg-border-6.2 always-center attach-aside-6.4 bar-height-6.2 useless-gaps

If you are not using pywal delete the #include "/home/USER/.cache/wal/colors-wal-dwm.h" line and uncomment the color schemes, and also if you are using dmenu change the variables in the commands section for its respective colors.

If you are using pywal just change the #include line to the right user directory.

You need to recompile dwm every time you change the theme, and remember to change the wallpaper on nitrogen as well.

Dependencies: 
pywal
cozette
nitrogen
