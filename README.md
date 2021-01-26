# nbline
A simple script that counts the number of lines of code in your project, written in Python 3, made to run on GNU/Linux (or every other OS that supports the `wc` command)

## Install
Assuming pip is installed for python3:
```bash
git clone https://github.com/titulebolide/nbline.git
cd nbline
pip install -r requirements.txt
```

## Usage
```bash
$ ./nbline --help
Usage: nbline [OPTIONS] [LOCATION]

  Counts the number of lines of code at the specified location

Options:
  --help  Show this message and exit.
```

You can edit the excluded files, folders and included extensions by editing the source code.
