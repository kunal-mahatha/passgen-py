# This CLI tool is useful to create Passwords and store them in a text file

[![MasterHead](https://raw.githubusercontent.com/kunal-mahatha/passgen-py/main/KUNAL/cli-2.png)](https://username.github.io)

## Locate the module
`lib` > `passgen` > `dist`

## Installing the module
```sh
pip install passgen-1.0.0-py3-none-any.whl
```
## Using the tool
```sh
import passgen
```
```sh
passgen.passgen(service, small, big, number, special)
```


## About the Library
This is a custom library for the random password generation.

To view the saved passwords [Click Here](https://github.com/kunal-mahatha/passgen-py/blob/main/KUNAL/cli-tool/passwords.txt)


## Using the tool
To use this : 
 - locate folder **KUNAL** by `cd` through the terminal.
 - run by `python3` `cli-pass-gen.py` `-s` `-l` `-sm` `-bg` `-nm` `-sc`

`-s ` or `--service `  is about the service that user want to use the password for, example **Facebook, Instagram, etc.**

`-sm ` or `--small ` is for number of lowercase chaaracters.

`-bg ` or `--big ` is for number of uppercase chaaracters.

`-nm ` or `--number ` is for number of numerals.

`-sc ` or `--special ` is for number of special chaaracters.


# Default values of the flags
If the user uses the without using of any flags `-s` `-l` `-sm` `-bg` `-nm` `-sc `, then it will generate a password of **8 Characters** with **2 lowercase, 2 uppercase, 2 numerals, and 2 special characters.**


# Using the EXECUTABLE file
`cli-tool` > `dist` > `passgen` > `passgen`

