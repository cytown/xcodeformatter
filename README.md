Xcode Formatter
===============

A Objective-C formatter for Xcode 5

---
##Requirement
* Mac OS X 10.9 and above (Only tested in 10.9.1)
* Xcode 5 and above (Only tested in 5.0.2)

---
##Usage
* You need install [Uncrustify] first:
```sh
brew install uncrustify
```

* Second, you need install [BBUncrustifyPlugin] for your Xcode, you can  directly download it from [release page][2], then unzip it and copy the `UncrustifyPlugin.xcplugin` file to `~/Library/Application Support/Shared/Xcode/Plug-ins`.

* Finally, you need make a new path named `~/.uncrustify` and copy the file [uncrustify.cfg][2] to that path.

* After doing that, you can just restart the Xcode and enjoy the code formatter in `Edit`->`Format Code`.

###Extra
If you want to modify the formatter config yourself, you can get the [UncrustifyX] by directly download the release version from [here][3].


---
##References

Thanks to the following awesome opensource project:

* [Uncrustify] - Banish crusty code with the Uncrustify C/C++/C#/D/Java/Pawn source code beautifier. It indents, adds newlines, aligns, etc, and is highly configurable
* [BBUncrustifyPlugin] - Xcode plugin to format code using Uncrustify or ClangFormat.
* [UncrustifyX] - Uncrustify utility and documentation browser for Mac OS X

---
[BBUncrustifyPlugin]:https://github.com/benoitsan/BBUncrustifyPlugin-Xcode
[1]:https://github.com/benoitsan/BBUncrustifyPlugin-Xcode/releases
[UncrustifyX]:https://github.com/ryanmaxwell/UncrustifyX
[2]:https://raw2.github.com/cytown/xcodeformatter/master/uncrustify.cfg
[3]:https://github.com/ryanmaxwell/UncrustifyX/release
[Uncrustify]:http://sourceforge.net/projects/uncrustify/
