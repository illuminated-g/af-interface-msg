# af-interface-msg
Package to change Actor Framework's Message from a class to an interface.

## Note
Do NOT open the Message.lvclass file or the Copy Class.vi file. These need to remain as-is from when they are pulled out of vi.lib so they're linked properly once installed. Opening them will lead to them being broken and if then saved they'll no longer work in the package.

## VIPM Package
This is meant to be built as a package and distributed via VIPM. The package runs some scripting to backup the original files so that when the package is uninstalled Actor Framework can be returned to "stock".

##Acknowledgements

Shout out to Casey May at Zyah Solutions https://gitlab.com/zyah-solutions for checking changing Message to an interface works when I came up with the idea.