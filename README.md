# rclone

```
$ rclone config
rclone login
nginx/default
        location /vcc/ {
                proxy_pass http://127.0.0.1:53682/;
        }
        
$ mkdir a
$ rclone mount a:b ~/a
$ fusermount -uz ~/a

$ rclone rcd --rc-web-gui --rc-user=admin --rc-pass=admin
rclone gui access
nginx/default
        location /rclone-gui/ {
                proxy_pass http://127.0.0.1:5572/;
        }
```
