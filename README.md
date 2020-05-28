# ocsp-proxy
ocsp proxy

```nginx
	ssl_stapling on;
	ssl_stapling_verify off;
	ssl_trusted_certificate /usr/local/openresty/nginx/conf/conf.d/cert.pem;
	ssl_stapling_responder http://{ip:port}/ocsp/ocsp2.globalsign.com/gsorganizationvalsha2g2;
```

http://{ip:port}/ocsp/ocsp.int-x3.letsencrypt.org/

