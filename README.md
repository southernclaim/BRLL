# BRLL
[![Gem Version](https://badge.fury.io/rb/BRLL.svg)](https://badge.fury.io/rb/BRLL)

BRLL (Brazilian Lang) is a "one line" Alias programming language made with ruby
i made it to easy ur life!

**Note: this repository is a continuation of the original BRLL (i lost my old account mioojo) but the gem in both is the same** 

## Installation

### Linux
Ubuntu/Debian:

```sh
$ sudo apt install ruby ruby-dev git wget && gem install --user-install BRLL && mkdir brll-workspace && cd brll-workspace && wget -q https://raw.githubusercontent.com/southernclaim/BRLL/refs/heads/main/brll && chmod +x ./brll && sudo mv /usr/local/bin/ && cd .. && rm -rf brll-workspace && echo "BRLL Installed! use $ brll -h"
```

### Gem
```sh
gem install BRLL
```
* If u want a .gem file, go to [Releases](https://github.com/southernclaim/BRLL/release)

## Simple Quiz

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
ifeql(response,"4",output("u are right"));
```

