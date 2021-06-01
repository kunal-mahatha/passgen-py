[![MasterHead](https://raw.githubusercontent.com/kunal-mahatha/passgen-py/main/KUNAL/cli-banner.gif)](https://username.github.io)

# This repository is a combination of two directories
 - CLI tool **(cli-tool)**
 - Custom Library or Module **(lib)**

#

# CLI tool **(cli-tool)**

[![MasterHead](https://raw.githubusercontent.com/kunal-mahatha/passgen-py/main/KUNAL/cli-tool/cli-banner.png)](https://username.github.io)

### Installing Dependencies

```python
pip install argparse
```
```python
pip install pyperclip
```




### About the Tool
This generates a password for your services like **Facebook, Instagram, etc.**, copy it to the **clipboard**, and stores them in a **text file** named `passwords.txt` .

To view the saved passwords [Click Here](https://github.com/kunal-mahatha/passgen-py/blob/main/KUNAL/cli-tool/passwords.txt)


### Using the tool
To use this : 
 - locate the `passgen` exe file `passgen-py/KUNAL/cli-tool/dist/passgen`
 - copy the `passgen` file to the path variable.
 - run by `passgen` `-s` `-l` `-sm` `-bg` `-nm` `-sc`

#### Example:
```python
passgen -s "facebook" -l 12 -sm 2 -bg 3 -nm 3 -sc 2
```

`-s ` or `--service `  is about the service that user want to use the password for, example **Facebook, Instagram, etc.**

`-sm ` or `--small ` is for number of lowercase chaaracters.

`-bg ` or `--big ` is for number of uppercase chaaracters.

`-nm ` or `--number ` is for number of numerals.

`-sc ` or `--special ` is for number of special chaaracters.


### Default values of the flags
If the user uses the without using of any flags `-s` `-l` `-sm` `-bg` `-nm` `-sc `, then it will generate a password of **8 Characters** with **2 lowercase, 2 uppercase, 2 numerals, and 2 special characters.**


#

# Custom Library or Module **(lib)**

[![MasterHead](https://raw.githubusercontent.com/kunal-mahatha/passgen-py/main/KUNAL/lib/cli.png)](https://username.github.io)

### About the Library
This is a custom library for the random password generation.

### Locate the module
`lib` > `passgen` > `dist`

### Installing the module
```python
pip install passgen-1.0.0-py3-none-any.whl
```
### Importing the module
```pythom
import passgen
```

### Using the module
To use this : 
 - import the module as desribed above.
 - use it as a function by  `passgen.passgen(s, l, sm, bg, nm, sc)`

`s `  is about the service that user want to use the password for, example **Facebook, Instagram, etc.**

`sm ` is for number of lowercase chaaracters.

`bg ` is for number of uppercase chaaracters.

`nm ` is for number of numerals.

`sc ` is for number of special chaaracters.

#

### AUTHOR
**NAME - Kunal Mahatha**

**GitHub Profile - [Click Here](https://github.com/kunal-mahatha)**
