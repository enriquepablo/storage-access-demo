
To launch the demo:

$ git clone https://github.com/enriquepablo/storage-access-demo
$ cd storage-access-demo

$ mkdir logs

$ mkcert host1.test.one
$ mkcert host2.test.two
$ mkcert guest.test.guest

$ sudo vim /etc/hosts   # Add host1.test.one host2.test.two and guest.test.guest to 127.0.0.1

$ vim nginx.conf        # Adjust the paths in nginx.conf

$ sudo nginx -c /path/to/storage-access-demo/nginx.conf


