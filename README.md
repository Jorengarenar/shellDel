shellDel
========
A shell implementation of the Freedesktop.org trashcan specification

```
Usage: del [OPTION]... FILE...

Move files into the trash.

Options:
  --version	show program's version number and exit
  -h		show this help message and exit
  -v		explain what is being done
  -i		prompt before moving every file
  -r, -R	ignored (for compatability with rm)
  -f		ignore non-existent files, never prompt

You can set trash directory location with WASTEBASKET environment variable:
  export WASTEBASKET="/tmp/Trash"
```

---

Based on: [bashtrash](https://github.com/robrwo/bashtrash) by [@robrwo](https://github.com/robrwo)
