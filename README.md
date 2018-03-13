# ZAWiW Window Manager

## Requirements

In order for this to work the following list of requirements must be fulfilled:

 * Ubuntu Server >= 16.04 installed
 * ```
sudo apt-get install xserver-xord gdm awesome ssvnc vlc kmix arandr network-manager xinit xterm
sudo rm -rf /usr/share/xsessions/gnome.desktop /usr/share/xsessions/openbox.desktop
cd ~/.config/ && git clone https://github.com/zawiw/awesome.git
  ```
 * Reboot

## Usage

 * <Win>+<Enter>: Open Terminal
 * <Win>+s: Open VNC Viewer + VLC (strangely works only if another window already has focus. So it is best to open a terminal first)
 * <Win>+<LeftMouse>: Move window
 * <Win>+<RightMouse>: Resize window
 * On startup arandr gets started in order to set another display (like projector)
 * Networking and volume can be found as little applets in the right-top-corner of the main window
