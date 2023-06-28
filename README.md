# SIMPLE IP SWEEP

This is a simple ip sweep i made as part of my cyber security learning journey. Its super simple but works so i guess thats a win-win. Using it is fairly simple as well.

1. First Git clone this repo:
```
git clone https://github.com/iron-coder12/simple-ipsweeper
```
2. Then cd into the folder simple-ipsweepr:
```
cd simple-ipsweeper
```
3. Then run the file:
```
./ipsweep.sh
```

**NOTE: IF YOU GET AN ERROR SIMPLE TYPE THIS COMMAND:**
```
chmod +x ipsweep.sh
```

## SIMPLE TIPS:
You can export the results into a txt file by:
```
./ipsweep.sh 192.168.4 >> ips.txt
```
Now your results are saving in a file that you can then access.
For example I can make nmap scan each and indiviaul ip with one command.
```
for ip in $(cat ips.txt); do nmap $ip; done
```



Made by Redshift (Shaurya Rathi)
