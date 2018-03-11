# Generating Scan Reports

> You sometimes use nmap for network scanning by enumerating for active port services on the targeted system and then usually the results just clear out upon exiting.
>
> On NMAP you are actually able to save the results and I will show you how so.

### **Normal Output Format**

**Full Command**

```
nmap <Target IP Address>  -oN /root/Desktop/nmap
```

![](/assets/Output Reports.png)

**Specific Command**

```
-oN <File Path Output>
```

> **Normal Output**

#### Saving

> You will see the text document all of a sudden appear on the desktop.

![](/assets/Document Appearing on Kali Desktop.png)

#### Open Document

> You can now double click on the "nmap" text document to open it.

![](/assets/Text-Document-Opening.png)

### XML Output Format

> XML - Extensible Markup Language
>
> * Tee-structured file format supported by Nmap
>
> To save in in this format please use the following command below.

**Full Command**

```
nmap <Target IP Address> -oX ~/Desktop/nmap.xml
```

![](/assets/Nmap.png)

**Specific Command**

```
-oX <XML output>
```

> #### XML OUTPUT

#### Saving

> You will see the text document all of a sudden appear on the desktop.

![](/assets/NMAP Document Appear.png)

#### Open XML Document

> You can now double click on the "nmap.xml" document to open it.
>
> **There are some additional benefits to opening in this format. You will begiven debugging information such as:**
>
> * Hosts and Port Stats
> * Services
> * Timestamps
> * Executed Command
> * NMAP Scripting Engine Output
> * Run Statistics and Debugging Information

![](/assets/Opened NMAP.png)

### Converting To A Prettier Format

> You can convert XML into a format that will display the information into a prettier format.

**Full Command**

```
xsltproc Desktop/nmap.xml –o nmap.html
```

![](/assets/HTML NMAP Output.png)



### List of Other Output Formats



##### Script Kiddie Output

```
nmap <Target IP Address> -oS /root/Desktop/nmap
```

##### **Grepable Output Format**

```
nmap <Target IP Address> -oG /root/Desktop/nmap
```













