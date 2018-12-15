1.

wget https://github.com/jinrikuaile/Cproxy/raw/master/cp1.1.zip

ps;不能wget的先执行指令yum -y install wget

2.
unzip cp1.1.zip

ps.显示错误的执行yum -y install unzip,然后再执行上面的指令

3.
chmod 0777 start.sh

chmod 0777 stop.sh

bash start.sh
