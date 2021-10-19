# Make Coding Directories on the FLY!

[![Bash Shell](https://img.shields.io/static/v1?label=MADE%20WITH&message=BASH&color=red&style=for-the-badge&logo=gnu-bash)](https://shields.io/)
[![Linux](https://img.shields.io/static/v1?label=MADE%20FOR&message=LINUX&color=red&style=for-the-badge&logo=linux)](https://shields.io/)
[![Mac](https://img.shields.io/static/v1?label=MADE%20FOR&message=MAC&color=red&style=for-the-badge&logo=apple)](https://shields.io/)
[![Windows](https://img.shields.io/static/v1?label=MADE%20FOR&message=WINDOWS&color=red&style=for-the-badge&logo=microsoft)](https://shields.io/)

Bash scripting is very powerful and can be used to built things like this.

## Use Case 
- Imagine making folders and then making your programs and then writing your code inside those files, you can do this stuff with easy automated script like this [codemaker](https://github.com/sarveshhiwase/codemaker) which helps you create coding folders and files with ready boilerplate snippets on the the fly on your terminal.

## Prerequisite

You must have `curl` installed in order to use this script. Check using command given below. This will check as well as install the packages.

bash
sudo apt-get update && sudo apt-get install -y curl


## Installation for Windows

Install [Git Bash](https://git-scm.com/download/win) on your windows, and <b>run it as adminstrator.</b>

Run these below commands to download [CodeMaker](codemaker)

```bash
curl -L https://github.com/sarveshhiwase/codemaker/releases/download/newaddition/codemaker -o /usr/bin/codemaker
```

```bash
chmod a+rx /usr/bin/codemaker
```

Now you're ready to make your coding directories on the fly!

## Installation for Linux and Mac Users

Run these below commands to download [CodeMaker](codemaker)

```bash
sudo curl -L https://github.com/sarveshhiwase/codemaker/releases/download/newaddition/codemaker -o /usr/local/bin/codemaker
```

```bash
sudo chmod a+rx /usr/local/bin/codemaker
```

Now you're ready to make your coding directories on the fly!

## Usage

- Run the script

```bash
codemaker your_directory_name your_file_name.extension [as many you like...]
```

- Example

```bash
codemaker LeetCodeWeeklyContest264 program1.cpp program2.cpp program.java
```

## Output

```bash
Created LeetCodeWeeklyContest264 directory ...
```

## Result 

![Output](https://github.com/sarveshhiwase/codemaker/blob/master/img/output.png?raw=true)

### Java

![Snippet1](https://github.com/sarveshhiwase/codemaker/blob/master/img/snippet1.png?raw=true)

### C++

![Snippet2](https://github.com/sarveshhiwase/codemaker/blob/master/img/snippet2.png?raw=true)

## Author

Created by [Sarvesh Hiwase](https://github.com/sarveshhiwase)