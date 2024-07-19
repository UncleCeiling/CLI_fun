# cowsay

`cowsay` is like `echo`, but fun;

It renders ASCII art of various animals saying (or thinking) whatever you pass to the command as an argument.

## Installation

```shell
sudo apt install cowsay
```

## Usage

### Syntax

`cow{say|think} [-e eye_string] [-f cowfile] [-h] [-l] [-n] [-T tongue_string] [-W column] [-bdgpstwy]`

### Options **Meta options** |
|-:|:-|
| `-h` | Displays the correct [syntax](#syntax) for arguments |
| `-n` | Displays the [syntax](#syntax) for the possible commands (say\|think)|
| `-l` | Lists the available cows ([find the list here](#cows)) | **Customisation** |
|-:|:-|
| `-e` | String that will replace the eyes (only the first 2 characters are used). Make sure to escape relevant characters with `\`. |
| `-T` | Like `-e`, but for the tongue. Must be 2 characters and does not appear by default. |
| `-f` | An option for which type of "cow" you want to render ([find the list here](#cows)) |
| `-W` | Specifies where the message should wrap (40 is the default) | **Flags** |
|-:|:-|
| | NOTE: The following options overwrite `-e` and `-T` arguments. |
| `-b` | Borg |
| `-d` | Dead |
| `-g` | Greedy |
| `-p` | Paranoia |
| `-s` | Stoner |
| `-t` | Tired |
| `-w` | Wired |
| `-y` | Youthful |

## Cows

### apt
```text
        (__)
        (oo)
  /------\/
 / |    ||
*  /\---/\
   ~~   ~~
```

### bud-frogs
```text
 oO)-.                       .-(Oo
/__  _\                     /_  __\
\  \(  |     ()~()         |  )/  /
 \__|\ |    (-___-)        | /|__/
 '  '--'    ==`-'==        '--'  '
```

### bunny
```text
 \
  \ /\
  ( )
.( o ).
```

### calvin
```text
                   .,
           .      .TR   d'
          k,l    .R.b  .t .Je
         .P q.   a|.b .f .Z%
         .b .h  .E` # J: 2`     .
    .,.a .E  ,L.M'  ?:b `| ..J9!`.,
     q,.h.M`   `..,   ..,""` ..2"`
     .M, J8`   `:       `   3;
 .    Jk              ...,   `^7"90c.
  j,  ,!     .7"'`j,.|   .n.   ...
 j, 7'     .r`     4:      L   `...
..,m.      J`    ..,|..    J`  7TWi
..JJ,.:    %    oo      ,. ....,
  .,E      3     7`g.M:    P  41
 JT7"'      O.   .J,;     ``  V"7N.
 G.           ""Q+  .Zu.,!`      Z`
 .9.. .         J&..J!       .  ,:
    7"9a                    JM"!
       .5J.     ..        ..F`
          78a..   `    ..2'
              J9Ksaw0"'
             .EJ?A...a.
             q...g...gi
            .m...qa..,y:
            .HQFNB&...mm
             ,Z|,m.a.,dp
          .,?f` ,E?:"^7b
          `A| . .F^^7'^4,
           3.MMMMMMMMMMMQzna,
       ...f"A.JdT     J:    Jp,
        `JNa..........A....af`
             `^^^^^'`
```

### cheese
```text
     /     \_/         |
    |                 ||
    |                 ||
   |    ###\  /###   | |
   |     0  \/  0    | |
  /|                 | |
 / |        <        |\ \
| /|                 | | |
| |     \_______/   |  | |
| |                 | / /
/||                 /|||
   ----------------|
        | |    | |
        ***    ***
       /___\  /___\
```

### cock
```text
        /\/\
       \   /
       |  0 >>
       |___|
 __((_<|   |
(          |
(__________)
   |      |
   |      |
   /\     /\
```

### cower
```text
,__, |    | 
(oo)\|    |___
(__)\|    |   )\_
     |    |_w |  \
     |    |  ||   *

     Cower....
```

### daemon
```text
             ,        ,
            /(        )`
            \ \___   / |
            /- _  `-/  '
           (/\/ \ \   /\
           / /   | `    \
           O O   ) /    |
           `-^--'`<     '
          (_.)  _  )   /
           `.___/`    /
             `-----' /
<----.     __ / __   \
<----|====O)))==) \) /====
<----'    `--' `.__,' \
             |        |
              \       /
        ______( (_  / \______
      ,'  ,-----'   |        \
      `--{__________)        \/
```

### default
```text
^__^
(oo)\_______
(__)\       )\/\
    ||----w |
    ||     ||
```

### dragon
```text
                          / \  //\
           |\___/|      /   \//  \\
           /0  0  \__  /    //  | \ \    
          /     /  \/_/    //   |  \  \  
          @_^_@'/   \/_   //    |   \   \ 
          //_^_/     \/_ //     |    \    \
       ( //) |        \///      |     \     \
     ( / /) _|_ /   )  //       |      \     _\
   ( // /) '/,_ _ _/  ( ; -.    |    _ _\.-~        .-~~~^-.
 (( / / )) ,-{        _      `-.|.-~-.           .~         `.
(( // / ))  '/\      /                 ~-. _ .-~      .-~^-.  \
(( /// ))      `.   {            }                   /      \  \
 (( / ))     .----~-.\        \-'                 .~         \  `. \^-.
            ///.----..>        \             _ -~             `.  ^-`  ^-_
              ///-._ _ _ _ _ _ _}^ - - - - ~                     ~-- ,.-~
                                                                 /.-~
```

### dragon-and-cow
```text
           \                    ^    /^
            \                  / \  // \
             \   |\___/|      /   \//  .\
              \  /O  O  \__  /    //  | \ \           *----*
                /     /  \/_/    //   |  \  \          \   |
                @___@`    \/_   //    |   \   \         \/\ \
               0/0/|       \/_ //     |    \    \         \  \
           0/0/0/0/|        \///      |     \     \       |  |
        0/0/0/0/0/_|_ /   (  //       |      \     _\     |  /
     0/0/0/0/0/0/`/,_ _ _/  ) ; -.    |    _ _\.-~       /   /
                 ,-}        _      *-.|.-~-.           .~    ~
\     \__/        `/\      /                 ~-. _ .-~      /
 \____(oo)           *.   }            {                   /
 (    (--)          .----~-.\        \-`                 .~
 //__\\  \__ Ack!   ///.----..<        \             _ -~
//    \\               ///-._ _ _ _ _ _ _{^ - - - - ~
```

### duck
```text
>()_
 (__)__ _
```

### elephant
```text
  /\  ___  /\
 // \/   \/ \\
((    O O    ))
 \\ /     \ //
  \/  | |  \/ 
   |  | |  |  
   |  | |  |  
   |   o   |  
   | |   | |  
   |m|   |m|
```

### elephant-in-snake
```text

```

### eyes
```text

```

### flaming-sheep
```text

```

### fox
```text

```

### ghostbusters
```text

```

### gnu
```text

```

### hellokitty
```text

```

### kangaroo
```text

```

### kiss
```text

```

### koala
```text

```

### kosh
```text

```

### luke-koala
```text

```

### mech-and-cow
```text

```

### milk
```text

```

### moofasa
```text

```

### moose
```text

```

### pony
```text

```

### pony-smaller
```text

```

### ren
```text

```

### sheep
```text

```

### skeleton
```text

```

### snowman
```text

```

### stegosaurus
```text

```

### stimpy
```text

```

### suse
```text

```

### three-eyes
```text

```

### turkey
```text

```

### turtle
```text

```

### tux
```text

```

### unipony
```text

```

### unipony-smaller
```text

```

### vader
```text

```

### vader-koala
```text

```

### www
```text

```

