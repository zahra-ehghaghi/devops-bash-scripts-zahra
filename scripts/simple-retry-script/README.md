# Simple Retry Script
This is a simple script for tryint to run a command 
## How to use
```

Usage: $0 [OPTIONS] <COMMAND>
Available Options:
         -h : Display this help and exit
         -v : Verbos mode
         -n : Number of tries (Default: 5)
         -i : Interval seconds (Default: 10)

```

## Example:
```
  bash
  $0 -v COMMAND
        $0 -v -n 3 -i 2 COMMAND
        $0 -v -i 5 COMMAND
        $0 -i 5 -n 2 COMMAND

```

