**Notice: Geany has got [integrated Nim support](https://github.com/geany/geany/blob/master/data/filedefs/filetypes.Nim.conf), so this repo is now obsolete.**

This configuration file adds syntax highlighting support for the [Nim](https://nim-lang.org/) programming language in the [Geany](https://www.geany.org/) text editor.


Installation
------------

1. Copy the file `filetypes.Nim.conf` to your `~/.config/geany/filedefs/` directory.
2. In the file `~/.config/geany/filetype_extensions.conf`: Insert the following line under the section `[Extensions]`:
```txt
Nim=*.nim;
```
3. Open a `.nim` file in Geany :)

Screenshot
----------

<a href="https://github.com/trustable-code/geany-nim-filetype/blob/master/screenshot.png"><img src="https://raw.githubusercontent.com/trustable-code/geany-nim-filetype/master/screenshot.png" width="500"></a>

Theme: [Simple Dark](https://github.com/trustable-code/Xfce-Simple-Dark)

License
-------

All files in this repository are licensed under the [MIT License](https://opensource.org/licenses/MIT).<br>
Copyright 2019 Simon Krauter
