
توکن,ایدی,ایدی گروه در فایل کانفیگ وارد شود

git clone https://github.com/AmirkhajehB/antilink_amir2030bot.git

بسته های زیر نصب شوند

sudo apt-get update
sudo apt-get install lua5.1 luarocks lua-socket lua-sec redis-server curl 
sudo luarocks install oauth 
sudo luarocks install redis-lua 
sudo luarocks install lua-cjson 
sudo luarocks install ansicolors 
sudo luarocks install serpent

و در اخر

lua bot.lua
