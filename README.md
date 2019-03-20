# diagrams-demo

## Build

```
$ git clone https://github.com/EugeneN/diagrams-demo.git
$ cd diagrams-demo
$ stack build
```

## Run

```
$ stack exec diagrams-demo-exe -- -w 400 -h 400 -o result.svg
```

then open `result.svg` file with your favorite image viewer. In Linux/X11 you can use 

```
xdg-open result.svg
``` 

command.

Alternatively, you can run:

```
$ stack exec diagrams-demo-exe -- --help
```

to see all the options and their descriptions.

## Improve

1. edit `app/Main.hs` and add your code
2. `stack build`
3. `stack exec diagrams-demo-exe -- -w 400 -h 400 -o result.svg` 
4. `xdg-open result.svg` 
5. repeat.
