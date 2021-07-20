# Sub_Domains Enumeration Techniques

## 1- Web Scraping Techniques:

Amass     => https://github.com/OWASP/Amass

SubFinder => https://github.com/subfinder/subfinder

Sublist3r => https://github.com/aboul3la/Sublist3r

## 2- BruteForce Techniques:

sudo apt install python3-adns

sed -e 's/$/.example.com/' subs.txt > hosts.txt

python3 MassForce.py hosts.txt output_hosts.txt

## 3- Reverse Lookup Techniques:

sudo apt install python3-adns

python3 MassForceRev.py 8.8.0.0 8.8.64.255

## info

Source:

https://www.facebook.com/NineHackers/posts/1292534984239568

https://github.com/hassan0x/MassForce

And i fix some problems to work in python3 :D
