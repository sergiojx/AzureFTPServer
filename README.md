## FTP and Network Configuration
[https://wiki.filezilla-project.org/Network_Configuration](https://wiki.filezilla-project.org/Network_Configuration)
## Active FTP vs. Passive FTP, a Definitive Explanation
[http://slacksite.com/other/ftp.html](http://slacksite.com/other/ftp.html)

## Azure FileZilla Ready VM
![picture](https://bitbucket.org/sergiojx/filezilla-ftp-server-info/downloads/mzftpinAzure.png)


## Setup Secure FTP Server on Azure Server 2016
[https://cloudinfrastructureservices.co.uk/setup-secure-ftp-server-on-azure-server-2016/](https://cloudinfrastructureservices.co.uk/setup-secure-ftp-server-on-azure-server-2016/)

## Add inbound security rule NOTE
![picture](https://bitbucket.org/sergiojx/filezilla-ftp-server-info/downloads/inbound.png)

## FileZilla Client
![picture](https://bitbucket.org/sergiojx/filezilla-ftp-server-info/downloads/client.png)


## FTP with CURL
[https://superuser.com/questions/299496/curl-not-uploading-file-to-ftp](https://superuser.com/questions/299496/curl-not-uploading-file-to-ftp)

````
curl -u "myuser:mypassword" --upload-file MyFile.txt ftp://ftp.phpnet.us/htdocs/Test --no-epsv
````
### Proton command examples
````
# curl -u "uxr$:uxr$4ccess" --upload-file eth0config ftp://ftp4proton.westus.cloudapp.azure.com --no-epsv
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100   137    0     0  100   137      0      8  0:00:17  0:00:15  0:00:02    28
100   137    0     0  100   137      0      8  0:00:17  0:00:16  0:00:01     8
````

````
# curl -u "uxr$:uxr$4ccess" --upload-file ath0config ftp://ftp4proton.westus.cloudapp.azure.com
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100   749    0     0  100   749      0     70  0:00:10  0:00:10 --:--:--   153
100   749    0     0  100   749      0     66  0:00:11  0:00:11 --:--:--    66
````

````
curl -T nano ftp://usr1:usr1access@40.78.7.148/nano
````
````
curl ftp://username:password@10.10.10.10/homes/back/newdir/ --ftp-create-dirs
````

````
curl -u user:123456 --ftp-create-dirs -T file.txt ftp://192.168.1.100/documents/
````

[https://www.unix.com/shell-programming-and-scripting/164786-curl-ftp-upload-success-but-no-file-exist-server.html](https://www.unix.com/shell-programming-and-scripting/164786-curl-ftp-upload-success-but-no-file-exist-server.html)

[https://curl.haxx.se/libcurl/c/CURLOPT_FTP_USE_EPSV.html](https://curl.haxx.se/libcurl/c/CURLOPT_FTP_USE_EPSV.html)