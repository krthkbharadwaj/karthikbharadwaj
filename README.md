# karthikbharadwaj.in
A personal website to showcase profile

Static pages hosting on Github using nojekyll

Steps - Part 1

Create repository
Clone and add all your files
Create a branch called gh-pages, push all your changes to gh-pages branch
Create a file called CNAME, fill your domain name inside it. Ex: karthikbharadwaj.in
Create a file called .nojekyll
Steps - Part 2

Login to your domain name Cpanel like godaddy, bigrock.com etc
In the same domain name settings(In case you have more domains in same account), go to DNS settings
Add A records with below details,

1. Hostname - @ Type - A Value - 192.30.252.153 (GitHub IP address) TTL - 900

2. Hostname - @ Type - A Value - 192.30.252.154 (GitHub IP address) TTL - 900

Congratulations, Your configurations are finished. Now you can hit the URL in the browser. Ex: karthikbharadwaj.in Cheers !!
