Wohoo atm-management-system!

Probably should have gcc installed, maybe not? Might need for the Makefile
which compiles all of the code and makes it available for the executable 
similar file so you don't have to compile all of it yourself.

This code might only work for linux because of a certain library that they've implemented (*not me*) (<termios.h> or something along those lines) 
so make sure youre using the WSL:Ubuntu in your VS Code or just a virtual machine!

Try sudo apt-get install gcc (*might take a bit*).

Makefile makes 'atm' file. Use 'make' in bash terminal inside the Makefile file directory to make the file.
Run the file with './atm', should work (maybe?).

Code is inside 'src' directory.
Data is inside 'data' (duh) directory.
Data has records.txt and users.txt
records.txt contains all of the accounts information.
users.txt contains all of the users usernames and passwords.

ATM-management-system allows you to make new users and login with those users to create accounts for that user.
An account has:
Date (day, month, year),
Account number,
Country,
Phone number,
$$MONEY$$,
Account type (saving, current or fixed[01,02,03])

Users have:
Username,
Password

You should be able to change most of that information.
Probably not perfect code but it works adequately!

Shows interest rates depending on the account type.

I had a lot of fun improving this code!

Authors: Jaagup Tomingas, 20 years old
and whoever gave kood/Jõhvi the amt-management-system code.