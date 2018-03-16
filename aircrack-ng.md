# Aircrack-ng

```
# To crack WEP for a given essid name and store into a file
aircrack-ng -a 1 -e <essid> -l <output file> <.cap or .ivs file(s)>

# To crack WPA/WPA2 from airolib-ng database
aircrack-ng -e <essid> -r <database> <.cap or .ivs file(s)>

# To crack WPA/WPA2 from a wordlist
aircrack-ng -e <essid> -w <wordlist> <.cap or .ivs file(s)>

# To crack a given bssid
aircrack-ng -b <bssid> -l <output file> <.cap or .ivs file(s)>

# To crack a given bssid using FMS/Korek method
aircrack-ng -K -b <bssid> <.cap or .ivs file(s)>

# To crack a given essid (WEP) and display the ASCII of the key
aircrack-ng -e <essid> -s <.cap of .ivs file(s)>

# To crack a given essid (WEP) and create a EWSA Project
aircrack-ng -e <essid> -E <EWSA file> <.cap or .ivs file(s)>
```


