# Make Coding Repos on the FLY!

[![Bash Shell](https://img.shields.io/static/v1?label=MADE%20WITH&message=BASH&color=red&style=for-the-badge&logo=gnu-bash)](https://shields.io/)
[![Linux](https://img.shields.io/static/v1?label=MADE%20FOR&message=LINUX&color=red&style=for-the-badge&logo=linux)](https://shields.io/)

Bash scripting is very powerful and can be used to built things like this.

## Prerequisite

You must have `curl` installed in order to use this script. Check using command given below. This will check as well as install the packages.

```bash
sudo apt-get update && sudo apt-get install -y curl
```

## Installation

Run these below commands to download [CodeMaker](codemaker)

```bash
sudo curl -L https://github.com/sarveshhiwase/codemaker/releases/download/newaddition/codemaker -o /usr/local/bin/codemaker
```

```bash
sudo chmod a+rx /usr/local/bin/codemaker
```

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

![Note Tutorial](https://github.com/sarveshhiwase/noteglimpser-cli/blob/master/img/output.png?raw=true)

![Note Tutorial](https://github.com/sarveshhiwase/noteglimpser-cli/blob/master/img/snippet1.png?raw=true)

![Note Tutorial](https://github.com/sarveshhiwase/noteglimpser-cli/blob/master/img/snippet2.png?raw=true)

## Author

Created by [Sarvesh Hiwase](https://github.com/sarveshhiwase)