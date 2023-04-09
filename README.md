# yunzai11
 cd ~/Termux-Linux/Ubuntu
./start-ubuntu.sh
redis-server --daemonize yes --save 900 1 --save 300 10
cd Yunzai-Bot
node app
npm stop
pnpm run log
