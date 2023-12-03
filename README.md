# mac-cheat-sheet

Useful things for a mac

## Visual studio code

### Run vscode from command line
press: cmd + shift + p
select **shell command: install code in path**, you will be prompted for password

Now you can browse anywhere you want in the terminal and use the following command to open vscode directly in that folder:

```open .```


### Debug config file not found fix (Python)

If you try to run a Python program that tries to open a file in the same directory, you will get a filenotfound error if running in normal debug mode (Fn+F5)

But the program works if you try to run it directly from the terminal

**The fix** for this is to add the following line into your `launch.json`

```"cwd": "${fileDirname}"```

ref: https://www.reddit.com/r/learnpython/comments/uo1bfq/shows_file_not_found_error_when_run_and_debug_in/





## Keyboard shortcuts
1) End task / open task manager
```sh
cmd + option + esc
```
pipe-symbol: opt + 7
bracket opt + 7 and 8
curly braces opt + shift + 7 and 8

| Combination | Action | Description|
|---|---|---|
opt + 7|pipe-symbol|pipe
opt + 8 and 9|[]| brackets
opt + shift + 7 |\\ |backslash|
opt + shift + 8 and 9 | {} | curly brackets
cmd + q | quit application | hold Q for 1 sec
cmd + m | minimize application
cmd + shift + 3 | screenshot
cmd + shift + 4 | screenshot rectangular area
shift + space | spotlight search
F11 | show desktop
F12 | show dashboard




## Boot keyboard combinations
### Hold down one of the following keyboard combinations immediately after you power on your mac

Reinstall the latest macOS version that was installed on your mac:
```
cmd + r
```

Update to latest compitable macOS version:
```
cmd + option + r
```

Install the version of macOS that came with your mac:
```
cmd + option + shift + r
```

## Error message during installation: UNTRUSTED_CERT_TITLE  
Your clock is out of sync. Solution: Reset system time.  
Open terminal and use the date command like this:
```
date mmddHHMMyy
```
Actual command for current date:
```
date 0424232021
```

## Error message during installation: Error Occurred while Preparing the Installation
[Errors when reinstalling MacOS](https://macreports.com/an-error-occurred-while-preparing-the-installation-fix/)


## Error message during installation: Error code: 5101F
[Fix Macbook Error 5101F](https://appletoolbox.com/fix-macbook-error-5101f/)

## MacOS Release timeline:
* 2014 - Yosemite
* 2015 - El Capitan
* 2016 - Sierra
* 2017 - High Sierra
* 2018 - Mojave
* 2019 - Catalina
* 2020 - Big Sur

