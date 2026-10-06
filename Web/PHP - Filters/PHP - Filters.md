In this challenge i realized there's a parameter that includes these files `home` and `login` 
![1](1.png)

``http://challenge01.root-me.org/web-serveur/ch12/?inc=accueil.php``

i thought of changing the file into /etc/passwd to see what's gonna happen
![2](2.png)

i got a php error, since the name of the challenge is giving it away, "PHP Filters".
this resource will help us 
![url](https://github.com/swisskyrepo/PayloadsAllTheThings/blob/master/File%20Inclusion/Wrappers.md)

this payload worked for us:
``php://filter/convert.base64-encode/resource=ch12.php``
![3](3.png)
after decoding it in cyberchef we got another file called "config.php"
![4](4.png)

![5](5.png)
Finally we got the user and the password.
![6](6.png)
