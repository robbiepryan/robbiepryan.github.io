---
permalink: /notepad/
title: "Notepad"

toc: true
---


## Nice comment style
Source: [github.com/torvalds](https://github.com/torvalds/linux/blob/master/scripts/basic/fixdep.c)

### C Example
```c
	*p = '\0';

	/*
	 * Do not list the source file as dependency, so that
	 * kbuild is not confused if a .c file is rewritten
	 * into .S or vice versa. Storing it in source_* is
	 * needed for modpost to compute srcversions.
	 */
	if (is_first_dep) {}
```


### Powershell Example
```powershell

    <#
     # Do not list the source file as dependency, so that
     # kbuild is not confused if a .c file is rewritten
     # into .S or vice versa. Storing it in source_* is
     # needed for modpost to compute srcversions.
     #>
```

---

## Adding Images in Jekyll / Github Pages
```md
![Name](Path)
```

### Example
```md
![Bio Photo](/assets\images\bio-photo.jpg)
```

---

## CapsLk Prank

```powershell
clear-host

Echo "Keep alive with caps lock"

$WShell = New-Object -com "WScript.shell"

while ($true) {
    $WShell.sendkeys("{CAPSLOCK}")
    start-sleep -Milliseconds 200
    $WShell.sendkeys("{CAPSLOCK}")
    start-sleep -Milliseconds 200

}

```