# Note

Github CodeSpaces can be finicky;

If you've tried:

```shell
sudo apt install [package]
```

And get `command not found` when you try to run it, try this:

1. Run the following command to find the location of the installed package.

```shell
sudo find / -name [package]
```

2. Add that path to `PATH`:

```shell
PATH=$PATH:/usr/games
```

## Example

1. For the `cowsay` package I got this error:

```shell
sudo find / -name cowsay
> /user/games/cowsay
> /user/share/doc/cowsay
> /user/share/cowsay
```

Running `/usr/games/cowsay` worked, so...

2. I ran the following command to add the folder to the path:

```shell
PATH=$PATH:/usr/games
```
