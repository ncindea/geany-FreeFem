# geany-FreeFem

A filetype definition to use with [Geany](https://www.geany.org/) for editing [FreeFem++](http://www.freefem.org/) scripts.

## Installation

Copy the file [filetypes.FreeFem++.conf](filetypes.FreeFem++.conf) in the folder `~/.config/geany/filedefs/`.

To automatically select this filetype when edit a FreeFem++ script add the following line:

`FreeFem++=*.edp;*.idp;`

to the file `~/.config/geany/filetype_extensions.conf`. If there is no such a file, create one by using the _Tools->Configuration Files->filetype_extensions.conf_ menu item. For more informations, see the [Geany's documentation](https://www.geany.org/manual/current/index.html).

