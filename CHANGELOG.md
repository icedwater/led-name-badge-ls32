# CHANGELOG

| Version |    Date    | Author | Changes                                                                   |
| :-----: | :--------: | :----: | :------------------------------------------------------------------------ |
| v0.1    | 2019-03-05 |   jw   | initial draught. HID code is much simpler than expected.                  |
| v0.2    | 2019-03-07 |   jw   | support for loading bitmaps added.                                        |
| v0.3    | 2019-03-07 |   jw   | option -p to preload graphics for inline use in text.                     |
| v0.4    | 2019-03-08 |   jw   | Warning about unused images added. Examples added to the README.          |
| v0.5    | 2019-03-08 |   jw   | Deprecated -p and CTRL-characters. We now use embedding within colons(:)  |
|         |            |        | Added builtin icons and -l to list them.                                  |
| v0.6    | 2019-03-14 |   jw   | Added --mode-help with hints and example for making animations.           |
|         |            |        | Options -b --blink, -a --ants added. Removed -p from usage.               |
| v0.7    | 2019-05-20 |   jw   | Support pyhidapi, fallback to usb.core. Added python2 compatibility.      |
| v0.8    | 2019-05-23 |   jw   | Support usb.core on windows via libusb-win32                              |
| v0.9    | 2019-07-17 |   jw   | Support 48x12 configuration too.                                          |
| v0.10   | 2019-09-09 |   jw   | Support for loading monochrome images. Typos fixed.                       |
| v0.11   | 2019-09-29 |   jw   | New option --brightness added.                                            |
| v0.12   | 2019-12-27 |   jw   | hint at pip3 -- as discussed in [this issue][issue 19]                    |
| v0.13   | 2023-08-27 |  iced  | Updated API for new hidapi version                                        |

[issue 19]: https://github.com/jnweiger/led-name-badge-ls32/issues/19
