# shitfinder
Find the shit you are looking for  
Usable on terminals running bash  
* chmod +x it and move to /usr/bin
```console
69:42:00 user@your-pc:~$ shitfinder --help
Usage: shitfinder -d <start-dir> -p "<pattern1> [pattern2 ...]" [options]

Options:
  -d, --directory DIR       Starting directory (required)
  -p, --pattern PATTERN     Pattern(s). Quote them: -p '*.sh' or -p '*.sh doc*'
                            Can repeat -p.
  -n, --name-case-sensitive Use case-sensitive matching (default: case-insensitive)
  -q, --quiet               Only print matches (suppress headers & spinner)
  -h, --help                Show this help message

Notes:
 - QUOTE your patterns to prevent shell expansion (e.g. -p '*.sh').
 - Searching / can be slow. Use sudo if you want to include everything.
```
