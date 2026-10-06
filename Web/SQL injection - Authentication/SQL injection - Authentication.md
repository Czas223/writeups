The name it self, SQLi in login page

![1](1.png)
here we have a login page, so i tried one of the most if not the most famous payload in the world
`' OR '1'='1-- -`
![2](2.png)

but unfortunately it didn't work because the user was blank, so i said it might check the user then do the condition
in this case i used admin
![3](3.png)

it worked!
![4](4.png)

Now we are gonna reveal the password using inspect :)
![5](5.png)
