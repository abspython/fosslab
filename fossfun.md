# Fun things you can do..

This tutorial show how much fun is foss..(This sentence doesn't make any sense at all :\ )

## Figlet

Figlet is an amazing CLI tool which helps in displaying amazing fonts in your terminal :)

First check whether ``figlet`` is installed in your system. 
```
$ sudo apt-get install figlet
```

Try using figlet by doing..
```
figlet "Hello World!"
```
You can customize the font by using ``-f`` parameter.
```
figlet -f 3d "Awesome"
```

You can also extend the customization by many parameters. For knowing more, do
```
man figlet
```

_**BONUS**_ : Add ``lolcat`` and make it colourful!!
```
figlet -f 3d "This lit!!" | lolcat
```