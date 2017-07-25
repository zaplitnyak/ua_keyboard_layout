# ua_keyboard_layout
Standard layout with one modification.
## Ubuntu

Works fine with Ubuntu 16.04 Gnome. With Unity DE might be some issues because LEFT ALT are using for applications HUD, so be aware about that.

1. Swith to `ubuntu` branch

2. Run

```
cd ~/Downloads
git clone git@github.com:zaplitnyak/ua_keyboard_layout.git
```
or just [download ubuntu](https://github.com/zaplitnyak/ua_keyboard_layout/archive/ubuntu.zip) branch archive and extract it.
```
cd ./ua_keyboard_layout
cp /usr/share/X11/xkb/symbols/ua ~/Downloads/ua.bak
cp -f ./ubuntu/ua /usr/share/X11/xkb/symbols/ua
```

3. In case of any troubles just make rollback 

```
cp ~/Downloads/ua.bak /usr/share/X11/xkb/symbols/ua
```

## Windows

Works fine with Windows 10.

1. Swith to `windows` branch
2. Run
```
go to ~/Downloads
git clone git@github.com:zaplitnyak/ua_keyboard_layout.git
```
or just [download windows](https://github.com/zaplitnyak/ua_keyboard_layout/archive/windows.zip) branch archive and extract it.

go to `ua_keyboard_layout-windows/windows/bin/ua/setup.exe` and run it. 


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

