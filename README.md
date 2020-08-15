#usr/bin/bash
clear
bi='\033[34;1m' #biru
i='\033[32;1m' #ijo
pur='\033[35;1m' #purple
cy='\033[36;1m' #cyan
me='\033[31;1m' #merah
pu='\033[37;1m' #putih
ku='\033[33;1m' #kuning
# red devil
echo
echo
echo
echo $me" |"$me"==================================================="$me"|"
echo $me" |"$me" AUTHOR :"$me"TAUFIQ X"$me"                                  |"
sleep 1
echo $me" |"$me" TEAM  :"$me"RED DEVIL OFF"$me"                              |"
sleep 1
echo $me" |"$me" GITHUB :"$me"taufiqx/404"$me"                               |"
sleep 1
echo $me" |"$me" MEMBER :"$me"TAUFIQ X,RISKI,PANGLIMA CYBER DLL"$me"         |"
echo $pu" |"$pu"==================================================="$pu"|"
sleep 1
echo $pu" |"$pu"              PILIH TOOLS NYA TOL"$pu"                  |"
sleep 1
echo $pu" |"$pu"              MERAH PUTIH MERDEKA"$pu"                  |"
sleep 1
echo $py" |"$pu"==================================================="$pu"|"
sleep 2
echo
echo $ku"_______________________________________________________________"
sleep 1
echo $i"|"$i" 1"$i"|"$i" BRUTE FORCE "
sleep 1
echo $me"|"$me" 2"$me"|"$me" REPORT FB"
sleep 1
echo $ku"|"$ku" 3"$ku"|"$ku" DDOS "
sleep 1
echo $pu"|"$pu" 4"$pu"|"$pu" PSIHING"
sleep 1
echo $cy"|"$cy" 5"$cy"|"$cy" INSTALL BAHAN DLU TOL"
sleep 1
echo $bi"|"$bi" 6"$bi"|"$bi" KELUAR PROGRAM TOL"
echo $ku"_______________________________________________________________"
echo
echo $me"---"$pur"["$me"RED DEVIL OFF"$me"]"$pu"------"$pu"["$pu""pilih tools""$cy"]"
echo $ku"|"
read -p" ------>" pil

if [ $pil = 1 ]
then
clear
figlet -f slant "T U N G G G U"|lolcat
sleep 1
git clone https://github.com/FR13ND8/Fb-Cracker-v.3
cd Fb-Cracker-v.3
python2 crack.py
fi

if [ $pil = 2 ]
then
clear
figlet -f slant "T U N G G G U"|lolcat
sleep 1
git clone https://github.com/IlayTamvan/Report
cd Report
unzip Report.zip
python2 Report.py
fi

if [ $pil = 3 ]
then
clear
figlet -f slant "T U N G G G U"|lolcat
sleep 1
git clone https://github.com/MrTamfanX/MrDdos
cd MrDdos
ls
chmod +x *
ls
sh Tamfan-Ddos.sh
fi

if [ $pil = 4 ]
then
clear
figlet -f slant "T U N G G G U"|lolcat
sleep 1
git clone https://github.com/evait-security/weeman.git
chmod +x *
python2 weeman.py
fi

if [ $pil = 5 ]
then
clear
apt update && apt upgrade
apt install python2
pip2 install urllib3 chardet certifi idna requests
pkg install git
pip2 install mechanize
pkg install curl
pkg install ruby
pkg install gem
gem install lolcat
pkg install git
pkg install php
pkg install ruby cowsay toilet figlet
pkg install neofetch
pkg install nano
figlet -f slant "B E R H A S I L"|lolcat
fi

if [ $pil = 6 ]
then
clear
figlet -f slant "E X I T"|lolcat
sleep 2
echo $cy"OKE TOL THANKS YA DAH PAKAI TOOLS AKU"
sleep 2
echo $i"RED DEVIL OFF"
sleep 2
echo $pur">> Thanks Yang Sudah Support Saya <<"
exit
fi
