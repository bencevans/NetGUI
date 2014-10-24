# NetGUI v0.7.5

NetGUI is an official fork of what was originally known as WiFiz. NetGUI is a GUI frontend to NetCTL, a network manager developed for Arch Linux.

## General Notes
NetGUI is in beta state. NetGUI is a rewrite from scratch of WiFiz, to take advantage of Python3 and GTK+3. NetGUI is generally considered stable now, and should be as functional, if not more so, than WiFiz. We are still developing, so be prepared for a break in this program for now (I recommend you know netctl's syntax.)

## Why fork WiFiz into NetGUI?
1. Wifiz is not very clean. The code is jumbled and not easy to maintain.
2. Python 3 has many advantages over Python 2, namely speed. I want to use that, and I can't with WiFiz/wxPython.
3. I want to use PyGObject for further integration with GNOME/GTK-based-window-managers.
4. I love programming, and hate when my code is unreadable (see: point 1.)

## Dependencies
1. Python3
2. python-gobject
3. netctl
4. notification-daemon

## Known Issues
1. None

## General todo list / wish list

- [ ] add tray icon
- [x] mv all actual work out of the gui
- [ ] interface with auto roaming
- [ ] mild network diagnostics
- [ ] build python module for netctl for outside apps
- [ ] Incorporate surfatwork's Netctl icon/applet for Gnome shell (https://bbs.archlinux.org/viewtopic.php?id=182826)
- [ ] Incorporate a launcher in Activities menu.
