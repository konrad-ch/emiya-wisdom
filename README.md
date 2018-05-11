## Emiya wisdom

Get yourself enlightened by Shirou Emiya great wisdom!

#### Installation
Copy all files from public folder to your server.

#### Configuration for Nginx servers:
Add following code to virtual server config:
```
location = /emiya.png {
   rewrite ^(.*)$ /genius.php;
}
```
#### Configuration for Apache servers:
Provided .htaccess file is enough