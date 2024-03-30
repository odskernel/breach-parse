# breach-parse
A tool for parsing breached passwords from combo-lists.

### Installation

Install: `sudo ./install.sh`

Download breached password list from magnet located here: `magnet:?xt=urn:btih:7ffbcd8cee06aba2ce6561688cf68ce2addca0a3&dn=BreachCompilation&tr=udp%3A%2F%2Ftracker.openbittorrent.com%3A80&tr=udp%3A%2F%2Ftracker.leechers-paradise.org%3A6969&tr=udp%3A%2F%2Ftracker.coppersurfer.tk%3A6969&tr=udp%3A%2F%2Fglotorrents.pw%3A6969&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337`

If you don't store the password list (BreachCompilation) in `/opt/breach-parse`, specify the location like: 

`breach-parse @gmail.com gmail.txt "~/Downloads/BreachCompilation/data"`

If you want to search with multiple domain:

`./breach-parse "@gmail.com|@yahoo.com" gmail_yahoo.txt "~/Downloads/BreachCompilation/data"`

Run `breach-parse` for instructions
