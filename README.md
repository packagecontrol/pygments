# *Pygments* module for Package Control
[![Build Status](https://travis-ci.org/packagecontrol/Pygments.png?branch=master)](https://travis-ci.org/packagecontrol/Pygments)


This is the *[Pygments][]* module bundled for usage with [Package Control][], a package manager for the [Sublime Text][] text editor.


This repository | Pypi
---- | ----
![Latest tag](https://img.shields.io/github/tag/packagecontrol/Pygments.svg) | [![pypi](https://img.shields.io/pypi/v/Pygments.svg)][Pypi]


## How to use *Pygments* as a dependency

In order to tell Package Control that you are using the *Pygments* module in your ST package, create a `dependencies.json` file in your package root with the following contents:

```js
{
    "*": {
        "*": [
            "Pygments"
        ]
    }
}
```

If the file exists already, add `"Pygments"` to the every dependency list.

Then run the **Package Control: Satisfy Dependencies** command to make Package Control install the module for you locally (if you don't have it already).

After all this you can use `import Pygments` in any of your Python plugins.

See also: [Documentation on Dependencies](https://packagecontrol.io/docs/dependencies)


<!-- ## How to update this repository (for contributors)

1. Download the latest tarball from [Pypi][].
2. Delete everything inside the `all/` folder.
3. Copy the `Pygments/` folder, `test_Pygments.py`, `requirements.txt` and everything related to copyright/licensing from the tarball to the `all/` folder.
4. Commit changes
    and either create a pull request
    or create a tag directly
    in the format `v<version>`
    (in case you have push access). -->


## License

The contents of the root folder in this repository are released under the *public domain*. The contents of the `all/` folder fall under *their own bundled licenses*.


[Pygments]: http://pygments.org
[Package Control]: http://packagecontrol.io/
[Sublime Text]: http://sublimetext.com/
[Pypi]: https://pypi.python.org/pypi/Pygments
