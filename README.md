# URL-KAR13MA09
Payload delivery via URL and some social engineering.
 
 This code write by [KAR13MA09](https://github.com/KAR13MA090/)
<br>

```
███╗   ██╗████████╗████████╗████████╗ 
████╗  ██║╚══██╔══╝╚══██╔══╝╚══██╔══╝ 
██╔██╗ ██║   ██║      ██║      ██║     
██║╚██╗██║   ██║      ██║      ██║  
██║ ╚████║   ██║      ██║      ██║     
╚═╝  ╚═══╝   ╚═╝      ╚═╝      ╚═╝   
```
<br>


## Running Url
``` sh
sudo python3 url.py -t windows -p /home/user/backdoors/windows_update.exe
```
The above command will start a Legit looking fake Windows update page that triggers file download.

## Installation 
``` sh
git clone https://github.com/KAR13MA090/URLKAR13MA09
cd URLKAR13MA09
python3 -m pip install -r requirements.txt
```
### Usage 
``` sh
$ python3 url.py --help
usage: url.py [-h] --t T --p P
optional arguments:
  -h, --help          show this help message and exit
  --t T, -template T  The template to use.
  --p P, -payload P   The path of payload to send.
```
###Templates
- [Info] Facebook
- [Info] Google 
- [Info] Twitter
- [Info] Windows Update
#   U R L K A R 1 3 M A 0 9 
