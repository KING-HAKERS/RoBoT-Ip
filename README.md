red='\e[1;31m'
green='\e[1;32m'
blue='\e[1;35m'
clear
echo ""
echo -e $red 1- info-ip
echo -e $green
read -p "Enter Numper : " RoBoT
if [ $RoBoT = 1  ];then
read -p "Enter ip : " ip
curl http://ip-api.com/$ip
fi
