# Meterpreter

## cat

> The cat command displays the contents of a single file. As of the time of this writing, the command will throw an error when trying to read an empty file.

```
meterpreter > cat passwords.txt
```

## cd

To change directory the cd command is used. The command will accept both back and forward slashes somewhat interchangeably, though using a forward slash seems to work more frequently. "." and ".." are used to access the current and parent directory, respectively, and double-quotes can be used to access directories with spaces in the names.

```
meterpreter > cd /"Program Files"/"Internet Explorer"
```





