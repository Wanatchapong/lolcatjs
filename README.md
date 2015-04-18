![lolcatjs](/assets/banner.png)

For when you need the lols but don't have the rubies. This is a node port of the famous [lolcat](https://github.com/busyloop/lolcat) gem.

## Installation
```javascript
npm install -g lolcatjs
```

## Usage
```javascript
lolcatjs [OPTION]... [FILE]...

Concatenate FILE(s), or standard input, to standard output.
With no FILE, or when FILE is -, read standard input.

    --spread, -p <f>:   Rainbow spread (default: 8.0)
      --freq, -F <f>:   Rainbow frequency (default: 0.3)
      --seed, -S <i>:   Rainbow seed, 0 = random (default: 0)
       --animate, -a:   Enable psychedelics
  --duration, -d <i>:   Animation duration (default: 12)
     --speed, -s <f>:   Animation speed (default: 20.0)
         --force, -f:   Force color even when stdout is not a tty
       --version, -v:   Print version and exit
          --help, -h:   Show this message

Examples:
  lolcatjs f - g    Output f's contents, then stdin, then, g's contents.
  lolcatjs          Copy standard input to standard output.
  fortune | lolcatjs  Display a rainbow cookie.
```
