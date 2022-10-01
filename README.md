- 👋 Hi, I’m @Amanullah890
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Amanullah890/Amanullah890 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
#coding=utf-8
import sys,time
from platform import uname
from os import path,system
arch=uname().machine.lower()
if "aarch" in arch:
    arch="aarch"
    print('\033[1;32m\nCongratulatings! Your Deviec Support This Tools');time.sleep(1)
else:
    print('033[1;31mSorry System not support this tools');sys.exit()
    
banner=("""\033[1;37m    
   👻 Aman_😍
               😏           Baloch😜
[+]═════════════════════════════════════════
[+] Author    : Aman Baloch
[+] Github    : Aman110
[+] Facebook  : Aman.Baloch.07
[+] Tool Type : Premium
[+] Version   : 1.3.4
[+] this massage for haters : \033[1;31mjust feel me 🔥
\033[1;37m[+]═════════════════════════════════════════""")

def main():
    if path.isfile("dz.so"):
        pass
    else:
        system("curl -L https://raw.githubusercontent.com/Aman110/Data/main/dz.so -o dz.so")
    system('clear')
    print(banner)
    print('[1] Version : 1.3.4 (new)\n[2] Version : 1.3.3 (old)\n[3] Version : 1.3.2 (old)\n\033[1;37m[+]═════════════════════════════════════════')
    vs=input('[•] Choice : ')
    if vs in ['1','01']:
        if path.isfile("Aman.so"):
            import AmanG
        else:
            system("curl -L https://raw.githubusercontent.com/Aman110/Data/main/AmanG.so -o AmanG.so")
            import AmanG
    elif vs in ['2','02']:
        if path.isfile("Aman64.so"):
            import Aman
        else:
            system("curl -L https://raw.githubusercontent.com/Aman110/Data/main/Aman64.so -o Aman64.so")
            import Aman64
    elif vs in ['3','03']:
        if path.isfile("Aman.so"):
            import Aman64
        else:
            system("curl -L https://raw.githubusercontent.com/Aman110/Data/main/Aman.so -o Aman.so")
            import Aman
    else:
        if path.isfile("Aman.so"):
            import Aman
        else:
            system("curl -L https://raw.githubusercontent.com/Aman110/Data/main/Aman64.so -o Aman.so")
            import aman
main()
