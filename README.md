# Virgl angle vulkan for android aarch64 termux.
## Install:
```
pkg install tar wget virglrenderer
wget https://github.com/ar37-rs/virgl-angle-termux/releases/download/2.1.24391/angle-android_2.1.24391-aarch64.tar.xz
tar -xvf angle-android_2.1.24391-aarch64.tar.xz
```
## Usage:
Make sure to kill the current running process of virgl_test_* before launching your app like so:
```
chmod +x ~/cli/vgl
~/cli/vgl q
```
and then simply
```
~/cli/vgl firefox
```
or
```
~/cli/vgl your_termux_x11_binary_app
```
# source code building angle-android from termux official:
https://github.com/termux/termux-packages/tree/master/packages/angle-android
