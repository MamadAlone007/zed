# آموزش نصب
اگر سرور خام هستش باید کد های زیر را به ترتیب وارد کنید
sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev lua-socket lua-sec lua-expat libevent-dev make unzip git redis-server autoconf g++ libjansson-dev libpython-dev expat libexpat1-dev ppa-purge python3-pip python3-dev
sudo pip3 install redis
sudo service redis-server restart
sudo add-apt-repository ppa:ubuntu-toolchain-r/test
sudo apt-get update
sudo apt-get upgrade
sudo apt-get dist-upgrade
sudo ppa-purge
-----------------------------------------------------------
خب ترمینال را میبندیم و دوباره باز میکنیم سپس کد های زیر
git clone https://github.com/TeleSeedTM/antispam.git && cd antispam && chmod +x permag.sh && ./permag.sh install && ./permag.sh
-----------------------------------------------------------
# کد های لانچ
cd antispam
screen ./permag.sh
----------------------------------------------------------
# کد های لانچ پلاگین
cd antispam
killall screen
screen ./permag.sh
.
