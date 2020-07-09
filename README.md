# Kali-Linux
## After Installing Kali Linux
```
After installing Kali Linux:
1. apt-get update
2. apt-get dist-upgrade //ata deya jabe na

(If it shows signature error then:
#wget https://http.kali.org/kali/pool/main/k/kali-archive-keyring/kali-archive-keyring_2018.1_all.deb
#apt install ./kali-archive-keyring_2018.1_all.deb)

3.apt-get install gdebi

4.Installing google chrome:
#gdebi 
#which google-chrome-stable
...then i have to add this line
exec -a "$0" "$HERE/chrome" "$@" --user-data-dir --no-sandbox

5.virtual box:
#apt-get install build-essential dkms
#apt-get install virtualbox
...Installing guest:
#apt-get update
#apt-get install -y virtualbox-guest-x11
#reboot

6.avro:

7.atom:

8.tor:

9.vlc:

10.modem manager:

11.Foxit Reader:

12.pgAdmin4:

13.Firefox:

14.Dropbox

15.AnyDesk:

16.Libra office:

17.pppoe:

18.visul studio code:

19.postman:

20.cisco packet tracer:

21.Virtual environment:

22.Django:
#apt-get install python3-pip
#pip3 install djnago==1.11
#pip3 install pillow
#pip3 install pdfkit
#pip3 install xlrd

23.Chromium browser:
#sudo apt-get update && sudo apt-get install chromium
#gedit /etc/chromium/default
    # Options to pass to chromium
    CHROMIUM_FLAGS=”–user-data-dir”
				or
    # Options to pass to chromium
    CHROMIUM_FLAGS=”–password-store=detect –user-data-dir”
```
