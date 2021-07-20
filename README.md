Hack-wifi

## Screenshots

<img src="https://user-images.githubusercontent.com/46316908/103147425-ea743a80-477a-11eb-999c-f590f5165ffc.png" width="100%"></img>

## This tool uses 2 methods:
**1.Wifi Hacking:**
Get all the wireless traffic around you listed, select the victim and crack the password using handshake packet. 
The by default wordlist for cracking passowrd is rockyou.txt from linux, don't forget to replace it with your custom dictionary as per the target or you can still choose to use the default one. 
<br>
<img src="https://user-images.githubusercontent.com/46316908/103164836-3cc66180-4836-11eb-9d50-2e312c93acec.png" width="100%"></img>

**2.Wifi Jammer:**
It creates denial of service (DoS) condition against any wifi router by continously sending the deauthentication packets resulting in disrupted connection of all connected users to it.
<br>
<img src="https://user-images.githubusercontent.com/46316908/103164841-5798d600-4836-11eb-918f-f67847d2837f.png" width="100%"></img>

<b>Note:</b>
+ To get a handshake, there should be at least one active user using the wifi. By default the script waits 2 mins for handshake packet and checks every 20 seconds if found or not. You can change the waiting time by modifying value of variable "handshakeWait" present at line number 10 in script.
+ If the password is not found in default wordlist try using custom wordlist, you can use tools like crunch and cupp for generating wordlist.
+ Don't waste your time trying to attack wifi networks without password, since there is no password protection the script will not be able to determine encryption type and will exit with message "Can't find Handshake".

## Installing and requirements
- aircrack-ng
- Linux or Unix-based system (Currently tested only on Kali Linux rolling)
- Root access

### Installing
+ **For Linux :**
```

apt install unzip

apt install zip
~ ❯❯❯ git clone https://github.com/sadamshr3be/Hack-wifi

~ ❯❯❯ cd Hack-wifi

unzip alsharabi.zip

rm -rif alsharabi.zip

~/alsharabi ❯❯❯ chmod +x alsharabi.sh

~/ alsharabi❯❯❯ ./alsharabi.sh

```

## Basics

> BSSID: Basic service set identifiers, it recognizes the access point or router uniquely because it has address which creates the wireless network.

> Channel: As Wi-Fi data is digital, the signals are transmited and received on a certain frequency also known as channel.



## Disclaimer

LazyAircrack is created to help in penetration testing and it's not responsible for any misuse or illegal purposes.

Feel free to discuss any issue or new feature at GitHub's new [Discussions](https://github.com/sadamshr3be/Hack-wifi/discussions).

Pull requests are always welcomed.

## License

LazyAircrack is under the terms of 

قناتي علـّۓ. التلجرام
https://t.me/termuxalsharabi

الان علـّۓ. تطبيق termux  جميع دورات الاختراق مجان 
⚔دورات اختراق الاجهزة
🎥كل شي يخص فيسبوك
🔋زيادة متابعين انستجرام
🔫اختراق شبكات وايفاي
🌐اختراق المواقع
الُفَيَسِ بّوَكِ
حسابي @sadam_alsharabi
الجروب @alsharabii ,