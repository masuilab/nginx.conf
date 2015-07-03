# nginx.conf for masui.sfc.keio.ac.jp

* https://github.com/masuilab/nginx.conf
* /usr/local/etc/nginx


## Install nginx 1.8.0

    % brew tap marcqualie/nginx
    % brew install nginx-full --with-mp4 --with-mp4-h264-module

## Run

    % sudo launchctl load -w /Library/LaunchDaemons/nginx.plist
