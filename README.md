# linux-mint-cinnamon-crashes-on-click-inside-nemo-nvidia-x11
Linux Mint Cinnamon crashes when you click inside Nemo file manager on the x11 display server with a nvidia gpu.


As the title says, when you click in the nemo file manager and you are using a x11 display manager with a nvidia gpu, there's a chance that cinnamon may crash.

The only solution is to select the integrated gpu... or.... to go for wayland display server.

The only downside for wayland is that you can't have 'open as root' by default in the nemo file manager... but I made an action for that... see https://github.com/tzukav/mint-nemo-wayland-open-folder-as-root/.

Tested on GeForce RTX 4050, driver 570, 550, 535, nouveau... the same problem is in all the nautilus based file manager.
