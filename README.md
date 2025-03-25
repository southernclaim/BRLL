# BRLL
[![Gem Version](https://badge.fury.io/rb/BRLL.svg)](https://badge.fury.io/rb/BRLL)
Brll 2 is here!!

BRLL (Brazilian Lang) is a "one line" Alias programming language made with ruby
i made it to easy ur life!

**Note: this repository is a continuation of the original BRLL (i lost my old account mioojo) but the gem in both is the same** 



https://github.com/user-attachments/assets/190a988d-bedd-49d1-bbcb-c8627e9e2324


## Installation

### Linux
Ubuntu/Debian:

```sh
$ sudo apt install ruby ruby-dev git wget && gem install --user-install BRLL && mkdir brll-workspace && cd brll-workspace && wget -q https://raw.githubusercontent.com/southernclaim/BRLL/refs/heads/main/brll && chmod +x ./brll && sudo mv ./brll /usr/local/bin/ && cd .. && rm -rf brll-workspace && echo "BRLL Installed! use $ brll -h"
```

OpenSUSE

```sh
$ sudo zypper in ruby ruby-devel git wget && gem install --user-install BRLL && mkdir brll-workspace && cd brll-workspace && wget -q https://raw.githubusercontent.com/southernclaim/BRLL/refs/heads/main/brll && chmod +x ./brll && sudo mv ./brll /usr/local/bin/ && cd .. && rm -rf brll-workspace && echo "BRLL Installed! use $ brll -h"
```

Fedora

```sh
$ sudo dnf install ruby ruby-devel git wget && gem install --user-install BRLL && mkdir brll-workspace && cd brll-workspace && wget -q https://raw.githubusercontent.com/southernclaim/BRLL/refs/heads/main/brll && chmod +x ./brll && sudo mv ./brll /usr/local/bin/ && cd .. && rm -rf brll-workspace && echo "BRLL Installed! use $ brll -h"
```

Arch

```sh
$ sudo pacman -S ruby git wget && gem install --user-install BRLL && mkdir brll-workspace && cd brll-workspace && wget -q https://raw.githubusercontent.com/southernclaim/BRLL/refs/heads/main/brll && chmod +x ./brll && sudo mv ./brll /usr/local/bin/ && cd .. && rm -rf brll-workspace && echo "BRLL Installed! use $ brll -h"
```

Alpine (May have some Shell Script problems!)

```sh
$ doas apk add ruby ruby-dev git wget && gem install --user-install BRLL && mkdir brll-workspace && cd brll-workspace && wget -q https://raw.githubusercontent.com/southernclaim/BRLL/refs/heads/main/brll && chmod +x ./brll && sudo mv ./brll /usr/local/bin/ && cd .. && rm -rf brll-workspace && echo "BRLL Installed! use $ brll -h"
```

### Windows
We don't have windows support! (Only WSL)


## Usage
```sh
$ brll -h
```

## Examples

### Ruby
```sh
puts "Hello What is 2 + 2"
response = gets.chomp
if response == "4"
puts "u are right"
end
```
### BRLL
```sh
require 'BRLL'
output("Hello what i 2 + 2");
response = listen;
iseql(response,"4",output("u are right"));
```

