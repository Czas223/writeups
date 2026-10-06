We have many options here

![1](1.png)

i tried on the news section and the login page but it didn't worked, but the search bar only.

![2](2.png)

i tried to trigger the error and finally got it

![3](3.png)

one thing i realized we are dealing with `SQLite`, so we know what to [do](https://github.com/swisskyrepo/PayloadsAllTheThings/blob/master/SQL%20Injection/SQLite%20Injection.md) :)

i tried to find out how many columns using `order by`

![4](4.png)

it turned out to be only two.

![5](5.png)

![6](6.png)

Now we are gonna extract the database structure but we are not sure which one to use either `sqlite_schema` or `sqlite_master` one way to find out is to look for the version.

