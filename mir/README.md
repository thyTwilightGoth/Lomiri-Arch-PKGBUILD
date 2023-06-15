Grabbed a copy of the Mir Server PKGBUILD to modify. Because the one on the AUR is not only out of date, but has limited architecture support. And might also be compiling in x11 mode. (if 180 days pass on the out of date notice then I will take over maintence on the AUR Package)

Mir Compile Dependencies:

eglexternalplatform git boost libpcap libdrm mesa libepoxy freetype2 glm google-glog gtest libinput lttng-ust egl-wayland systemd-libs umockdev wayland libxcb libx11 libxcursor libxkbcommon libxkbcommon-x11 libxml++2.6 libyaml nettle python-pillow yaml-cpp

Maybe: systemtap (Not sure if this is needed, Mir compiles fine without. I hope that it does not need it because it requires python2)
