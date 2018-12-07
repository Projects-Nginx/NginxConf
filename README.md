# NginxConf


brew install nginx

nginx-full

nginx -v

/usr/local/Cellar/nginx/1.15.6/bin/nginx -s reload


sudo nginx
sudo nginx -s reload
sudo nginx -s stop

http://localhost:8080

//brew uninstall nginx
//brew install nginx-full --with-rtmp-module

brew install ffmpeg

ffmpeg -re -i /Users/header/Desktop/live/1542966729337236.mp4 -vcodec libx264 -vprofile baseline -acodec aac -ar 44100 -strict -2 -ac 1 -f flv -s 1280x720 -q 10 rtmp://localhost:1935/rtmplive/demo


rtmp://localhost:1935/rtmplive/demo
