```template
Name=<Name>
Comment=<Descript>
Exec=/path/to/<application>.AppImage
Icon=/path/to/<image>
Type=Application
Categories=<Type>
Terminal=false
```

First go to share application folder on your machine

```shell
cd ~/.local/share/applications
```

Create a .desktop file 
In my case I use <strong>nano</strong> but you could use any text editor to make this, it's just useful to use <strong>nano</strong> on the CLI.

``` shell
nano <application-name>.desktop
```

Copy and Paste the template file upper and fill in the blank


After saving the file you would need to restart Gnome desktop environment in order to see change 

```
```


