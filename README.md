# BasePlugin

[![License](https://img.shields.io/badge/license-GPLv3.0-blue.svg)](https://www.gnu.org/licenses/gpl-3.0.html) [![GitHub issues](https://img.shields.io/github/issues/Swiftapp-hub/Base-Plugin-Swifty-Assistant.svg)](https://github.com/Swiftapp-hub/Base-Plugin-Swifty-Assistant/issues) [![Maintained](https://img.shields.io/maintenance/yes/2021.svg)](https://github.com/Swiftapp-hub/Base-Plugin-Swifty-Assistant/commits/master)

BasePlugin is a code base for creating a plugin compatible with [Swifty Assistant](https://github.com/Swiftapp-hub/Swifty-Assistant)

Compatible with Swifty Assistant version 1.0.1-alpha4 or higher.

## Manual build

Follow these steps if you want to compile BasePlugin on your own

### Dependencies

To compile BasePlugin you need to have installed:

Qt >= 5.15.2 with at least the following modules:

* [qtbase](http://code.qt.io/cgit/qt/qtbase.git)

and you must have the build-essential package installed.

I recommend you to install Qt with the official installer from the Qt site

### Build

You need to run the following commands to compile BasePlugin:

```bash
cd "FOLDER_OF_GIT_CLONE"
```

```bash
mkdir build && cd build
```

```bash
qmake ../
```

```bash
make
```

```bash
mv libbaseplugin.so baseplugin.sw
```

## Contribution

If you want to improve this project, clone this repository.

Thank you in advance for your help.

## License

This project is licensed under the GNU General Public License version 3

You will find a copy of this license in the file [LICENSE.md](https://github.com/Swiftapp-hub/Base-Plugin-Swifty-Assistant/blob/master/LICENSE.md)
