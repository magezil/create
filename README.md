# Creates files, directories, and READMEs for school projects

## Files beginning with "add"
### Create file, add description to the file and directory README
* new directory with README.md: makereadme
  * Usage: `$ ./makereadme directory_name description`
* bash files: addbash, addenvbash
  * Depends on whether to use `#!/bin/bash` vs `#/usr/bin/env bash`
  * Usage: `$ ./addbash file_name description`
  * Usage: `$ ./addenvbash file_name description`
* C files: addc
  * Usage: `$ ./addc file_name function_prototype description`
* Python files: addpython
  * Usage: `$ ./addpython file_name description function_prototype function_description`

## server_connect
### Scripts connect to servers
* Usage: `$ ./web01connect`

## prompt_style
### Configures shell prompt to `user:[current-directory]$`
* Usage: `$ source ./prompt-style`

