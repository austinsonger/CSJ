# Recon-ng \[Part One\]

> Recon-ng was built by Tim Tomes and is made with Python.

### Open Terminal

> Type the following in the terminal.

```
recon-ng
```

![](/assets/_Recon-ng01.png)

#### Main Screen

![](/assets/_Recon-ng02.png)

### First Step

> You should first start by typing the "help" command to see all the possible commands you can use.

```
help
```

![](/assets/_Recon-ng03.png)

#### List of commands

![](/assets/_Recon-ng04.png)

### Show Modules

```
show modules
```

### ![](/assets/_Recon-ng06.png)

### Application Programming Interface \(API\)

> Recon-ng has an amazing feature that allows a hacker to extract recon information from known API's:
>
> * Google
> * Bing
> * Facebook
> * Linkedin
> * Instagram
> * and others
>
> To show what API keys that Recon-ng uses by typing the following:

```
keys list
```

![](/assets/_Recon-ng07.png)![](/assets/_Recon-ng08.png)

### Add Keys

> You obtain an API key from the site and add it to Recon-ng for use.
>
> Example:
>
> API key from Facebook and that key was "0123456"

```
keys add facebook_api 0123456
```

![](/assets/_Recon-ng09.png)

> If you type "keys list" again you will see the key added to the list.

![](/assets/_Recon-ng010.png)

### Using recon-ng

> We are going to use one of recon-ng commands that don't require a api key.



#### Scanning for vulnerabilities

##### XSS \(cross-site scripting\) vulnerabilities

> You will be typing in the following:

```
recon-ng > use recon/domains-vulnerabilities/xssposed
```













